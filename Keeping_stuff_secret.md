# Keeping Stuff Secret

1. Two parties code in memory(code) and server database on internet(server)
2. Code wants to get information without the user seeing from server
3. So code makes a private and public key 
4. And tells server to use public key to encrypt information and send to code
5. Server encrypts information and sends to code
6. Use or man-in-middle cannot read information
7. Code decrypts information using private key
8. Code uses information over TSL
9. Code erases information and keys from memory

# Stopping tampering
1. When code installed user has to register with server
2. code calculates and shares installed code fingerprint in secret with server
3. Server registers fingerprint with user
4. Then in future server uses user fingerprint to obfuscate information
5. And code recalculates and uses fingerprint to de-obfuscate information
6. This ensures that unchanged client is used for communication