# Nonce Encrypter
A lightweight tool to encrypt nonce with AES-CBC for IBM Hyper Protect Crypto Services.

# Usage
Use the binaries in the release or build it yourself (see the next section),  all what you need to do is the following:
```shell
./nonce-encrypter -nonce "${NONCE}" -key "${KEY_MATERIAL}" -alg CBC
```

# Build
When building the tool, nothing special is needed, it is pretty straight forward:
```shell
GOOS=darwin GOARCH=amd64 go build
```
Or even just run it directly without the need to build it:
```shell
go run main.go -key "${KEY_MATERIAL}" -nonce "${NONCE}" -alg CBC
```