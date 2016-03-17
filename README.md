# silver_smuggler
Simple XOR file encryption/decryption. A simple app I made to learn Qt. 

This is a very simple application that allows you to encrypt and decrypt files with XOR. XOR is TRIVIALLY BREAKABLE and if you use this for anything that actually needs to be secret, you are fully responsible for all the awful things that will happen to you.

The process: the user selects a file, which is encrypted and encoded with Base64. The Base64 text representation of the encrypted bytes can be sent to the recipient or stored. To decrypt, a user simply enters the key and pastes in the Base64 ciphertext. The Base64 representation is turned back into bytes, decrypted, and written out.

I wrote this app in order to learn Qt. It worked quite well, I think.
