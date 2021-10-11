### S3 Encryption

## Encryption approches:

# Encryption at rest:

> Encryption at rest is designed to prevent the attacker from accessing the unencrypted data by ensuring the data is encrypted when on disk.

> If an attacker obtains a hard drive with encrypted data but not the encryption keys, the attacker must defeat the encryption to read the data.

> This attack is much more complex and resource consuming than accessing unencrypted data on a hard drive. 

>For this reason, encryption at rest is highly recommended and is a high priority requirement for many organizations

# encryption in transit:

> protects your data if communications are intercepted while data moves between your site and the cloud provider or between two services.

> This protection is achieved by encrypting the data before transmission; authenticating the endpoints; and decrypting and verifying the data on arrival. 

>For example, Transport Layer Security (TLS) is often used to encrypt data in transit for transport security, and Secure/Multipurpose Internet Mail Extensions (S/MIME) is used often for email message security.

# Concepts:

  `Plain text`-unencrypted data load intlo application and use

  `Algorithm`-piece of maths,encrypted data

  `key`- credentials(keys)

  `Ciphertext`: NO text data, encrypted data
            - Encryption uses these plain text,algorithm,key to make ciphertext.

# Symmetric encryption

>This is said to be the simplest and best-known encryption technique. As discussed already, it uses one key for both encryption and decryption.

>Because the algorithm behind symmetric encryption is less complex and executes faster, this is the preferred technique when transmitting data in bulk.

>The plaintext is encrypted using a key, and the same key is used at the receiving end to decrypt the received ciphertext.

> The host in the communication process would have received the key through external means.

> Widely used symmetric encryption algorithms include AES-128, AES-192, and AES-256.

# Asymmetric encryption

> This type of encryption is relatively new as compared to symmetric encryption, and is also referred to as public-key cryptography.

> Asymmetric encryption is considered to be more secure than symmetric encryption as it uses two keys for the process.

> The public key used for encryption is available to everyone but the private key is not disclosed.
> This encryption method is used in everyday communication over the internet.

> When a message is encrypted using a public key, it can only be decrypted using a private key.

> However, when a message is encrypted using a private key, it can be decrypted using a public key.

> Digital certificates in the client-server model can be used to discover public keys.

> The drawback of this encryption is that it takes more time than the symmetric encryption process.

> Common asymmetric encryption techniques include RSA, DSA, and PKCS.

# S3 encryption:

Amazon S3 supports both server-side encryption (with three key management options: SSE-KMS, SSE-C, SSE-S3)
                                           and
  client-side encryption for data uploads.

 Amazon S3 offers flexible security features to block unauthorized users from accessing your data.
   
    Use VPC endpoints to connect to S3 resources from your Amazon Virtual Private Cloud (Amazon VPC).
    
     Use S3 Inventory to check the encryption status of your S3 objects 