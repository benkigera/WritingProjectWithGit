#End to End

When whatsapp application is first installed it generates both a public and a private key. It stores the private key locally on the device and shares the public key with the whatsapp servers. Any person that wants to send a message through whatsapp will first request the server for my public key. He will then use the public key to encrypt his/her message. 

The server will then relay the encrypted message to my device. Once the encrypted message is received, my device will then use the private key to decypt the incoming message and it will be displayed to me as a normal text.

The concept reliest on the RSA algorithm.


The receiver who published the public key and kept a copy of the private is able to decrypt the message using the private key. 


