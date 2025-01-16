# clinicalencryption
Este código crea una página web para encriptar y desencriptar archivos usando el algoritmo AES (Advanced Encryption Standard) en modo CBC (Cipher Block Chaining) con relleno PKCS7. El usuario carga un archivo, ingresa una clave secreta y elige si quiere encriptar o desencriptar el archivo.
Este código HTML implementa una página web para encriptar y desencriptar archivos utilizando un método de cifrado simétrico AES (Advanced Encryption Standard) con el modo CBC (Cipher Block Chaining) y el relleno PKCS7. A continuación, te explicaré cada parte del código.

Método de encriptación utilizado:
El método de encriptación que se utiliza en este código es AES (Advanced Encryption Standard), específicamente en modo CBC (Cipher Block Chaining). El cifrado simétrico AES usa la misma clave tanto para encriptar como para desencriptar los datos. El modo CBC es un modo de operación que mejora la seguridad del cifrado AES al incorporar un IV (Vector de Inicialización) que se usa para garantizar que el mismo texto plano no produzca el mismo texto cifrado cada vez.

Cifrado AES CBC:
AES: Se utiliza para cifrar y descifrar los datos.
Modo CBC: Un modo de operación de cifrado en bloques que utiliza un IV (Vector de Inicialización) para encadenar los bloques de cifrado, lo que hace que cifrados iguales no generen el mismo resultado en el texto cifrado.
Relleno PKCS7: Es un estándar utilizado para completar los bloques de datos para que coincidan con el tamaño de bloque esperado de AES (16 bytes).
