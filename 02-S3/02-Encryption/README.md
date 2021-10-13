# S3 Encryption

## Encryption approches:

## Encryption at rest:

> Encryption at rest is to prevent the attacker from accessing the unencrypted data by ensuring the data is encrypted when on disk.

> any physical tampering or laptop theft

> with out passcode or keys attackers can`t do anything

## encryption in transit:

> these service is used only when multiple individuals are involved

> protects your data if communications data moves between your site and the cloud provider or between two services.

> when the transfering is done in tunnel between two points

> if one end is encrypted and the other will be decrypted

> in the middle attackers can`t do anything

## Concepts:

| Plain text | Algorithm | key | Ciphertext |
| ---------- | --------- | --- | ----------|
| unencrypted data load intlo application and use | Algorithm piece of maths,encrypted data | key credentials(keys) | NO text data, encrypted data Encryption uses these plain text,algorithm,key to make ciphertext |

## Symmetric encryption

>This is simplest and best-known encryption technique. it uses one key for both encryption and decryption.

>Because the algorithm behind symmetric encryption is less complex and executes faster, this is atechnique when transmitting data in bulk.

>The plaintext is encrypted using a key, and the same key is used at the receiving end to decrypt the received ciphertext.

> The host in the communication process would have received the key through external means.

> Widely used symmetric encryption algorithms include AES-128, AES-192, and AES-256.

## Asymmetric encryption

> This type of encryption is new as compared to symmetric encryption, and it is public-key cryptography.

> Asymmetric encryption is considered to be more secure than symmetric encryption as it uses two keys for the process.

> The public key used for encryption is available to everyone but the private key is not available.

> This encryption method is used in everyday communication over the internet.

> When a message is encrypted using a public key, it can only be decrypted using a private key.

> when a message is encrypted using a private key, it can be decrypted using a public key.

> Digital certificates in the client-server model can be used to discover public keys.

> The drawback of this encryption is that it takes more time than the symmetric encryption process.

> Common asymmetric encryption techniques include RSA, DSA, and PKCS.

## S3 encryption:

> Amazon S3 supports both server-side encryption (with three key management options: SSE-KMS, SSE-C, SSE-S3)
                                           and
  client-side encryption for data uploads.

> Amazon S3 offers flexible security features to block unauthorized users from accessing your data.
   
   - Use VPC endpoints to connect to S3 resources from your Amazon Virtual Private Cloud (Amazon VPC).
    
   - Use S3 Inventory to check the encryption status of your S3 objects 