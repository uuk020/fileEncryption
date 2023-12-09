# fileEncryption

This is a file encryption and decryption tool written in Go.

### Usage
1. Compile the source code
    ```bash
    go build -o fileEncryption main.go
    ```
2. Encrypt a file
    ```bash
    ./fileEncryption -m=encryption -f=path/to/file -p="password"
    ```
3. Decrypt a file
    ```bash
    ./fileEncryption -m=decryption -f=encrypted/file -p="password"
    ```

### Reference Project
1. [utools-fileEncryption](https://github.com/xiaou66/utools-fileEncryption)
