# clinicalencryption

This code creates a web page to encrypt and decrypt files using the AES (Advanced Encryption Standard) algorithm in CBC (Cipher Block Chaining) mode with PKCS7 padding. The user uploads a file, enters a secret key, and chooses whether to encrypt or decrypt the file. This HTML code implements a web page for encrypting and decrypting files using the AES symmetric encryption method in CBC (Cipher Block Chaining) mode with PKCS7 padding. Below, I will explain each part of the code.

**Encryption Method Used:**  
The encryption method used in this code is AES (Advanced Encryption Standard), specifically in CBC (Cipher Block Chaining) mode. AES symmetric encryption uses the same key for both encrypting and decrypting the data. CBC mode is an encryption operation mode that enhances AES security by incorporating an IV (Initialization Vector), which ensures that the same plaintext does not always produce the same ciphertext.

**AES CBC Encryption:**  
- **AES:** Used to encrypt and decrypt data.  
- **CBC Mode:** A block cipher mode of operation that uses an IV (Initialization Vector) to chain encryption blocks, ensuring that identical plaintexts do not produce the same ciphertext.  
- **PKCS7 Padding:** A standard used to pad data blocks to match AES’s expected block size (16 bytes).  
______________________________________________________
______________________________________________________

Este código crea una página web para encriptar y desencriptar archivos usando el algoritmo AES (Advanced Encryption Standard) en modo CBC (Cipher Block Chaining) con relleno PKCS7. El usuario carga un archivo, ingresa una clave secreta y elige si quiere encriptar o desencriptar el archivo.
Este código HTML implementa una página web para encriptar y desencriptar archivos utilizando un método de cifrado simétrico AES (Advanced Encryption Standard) con el modo CBC (Cipher Block Chaining) y el relleno PKCS7. A continuación, te explicaré cada parte del código.

Método de encriptación utilizado:
El método de encriptación que se utiliza en este código es AES (Advanced Encryption Standard), específicamente en modo CBC (Cipher Block Chaining). El cifrado simétrico AES usa la misma clave tanto para encriptar como para desencriptar los datos. El modo CBC es un modo de operación que mejora la seguridad del cifrado AES al incorporar un IV (Vector de Inicialización) que se usa para garantizar que el mismo texto plano no produzca el mismo texto cifrado cada vez.

Cifrado AES CBC:
AES: Se utiliza para cifrar y descifrar los datos.
Modo CBC: Un modo de operación de cifrado en bloques que utiliza un IV (Vector de Inicialización) para encadenar los bloques de cifrado, lo que hace que cifrados iguales no generen el mismo resultado en el texto cifrado.
Relleno PKCS7: Es un estándar utilizado para completar los bloques de datos para que coincidan con el tamaño de bloque esperado de AES (16 bytes).
