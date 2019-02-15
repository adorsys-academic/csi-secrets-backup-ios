# iOS-secrets-backup

In his thesis Stefan Haßferter evaluated a solution for backing up secrets by distributing partial backups to devices of trusted persons over peer-2-peer communication. This approach can be seen as a proposition to the urgent demand for a backup strategy which allows owners of crypto currencies to secure the access to their private keys without relying on a centralised storage provider. In the course of writing his thesis Stefan Haßferter implemented a functional prototype on iOS as a proof of concept.

#Abstract 

This thesis deals with the conception and implementation of a backup method for crypto cur- rency private keys. These represent the login data for the assets stored on the blockchain and are usually stored in a wallet, which is a program very similar to an online banking app. Just like this, it is often installed on the users’ smartphone. If access to the key becomes unavailable due to loss or destruction of the device, stored assets can no longer be disposed of. Since the probability of recovering the key by guessing is close to zero, it is almost impossible to regain access. For this reason, appropriate measures should be taken to back up and ensure recovery of the key. It is targeted to make these securely and conveniently available to the user by the application described in this paper. The basic idea is to split the key into parts and store them on the devices of trusted third parties. For recovery a subset of these parts must be combined. It is described which methods are used to create a backup and which encryption and communica- tion mechanisms are currently used. These include, among others, the RSA encryption method and the direct and indirect communication channels. In addition, the requirements regarding security and usability for a program of this kind are elaborated. Based on this, suitable com- ponents are selected and implemented. A further central point is the functional description of the Shamir’s Secret Sharing Scheme (SSSS) algorithm and its application to the creation of backup copies. Moreover, possible program extensions are presented.
