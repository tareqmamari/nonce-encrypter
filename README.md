# Nonce Encrypter
A lightweight tool to encrypt nonce with AES-CBC for IBM Hyper Protect Crypto Services

# Usage
Use the binaries in the release or build it yourself (see the next section),  all what you need to do is the following:
```
./nonce-encrypter -nonce "${NONCE}" -key "${KEY_MATERIAL}" -alg CBC
```