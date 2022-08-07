# Encrypt Decrypt Website mini project

## Usage
Use this web page to encrypt a file using a password, then use the same password later to decrypt the file. IMPORTANT: The same password that was used to encrypt the file must be used to decrypt the file later. If you loose or forget the password, it cannot be recovered!

## Cryptography

All client-side cryptography is implemented using the Web Crypto API. Files are encrypted using AES-CBC 256-bit symmetric encryption. The encryption key is derived from the password and a random salt using PBKDF2 derivation with 10000 iterations of SHA256 hashing.

## Running the page offline

The web page is self-contained. The page does not require any supporting files; all javascript and css for the page is contained in the source code of the page. 
To run the page locally on your system offline, simply save the page to your system as a .html file, then open the file from your system in your web browser (optionally with networking disabled).

## LINK : 
