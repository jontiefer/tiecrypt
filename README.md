# XCrypt (7-Zip Based AES-256 Encryption/Decryption)
### <i>Jonathan Tiefer - Copyright (c) 2021-2022</i>

### This program uses the 7-Zip program, including 7z.exe and 7z.dll to perform compression and encryption.  7-zip is licensed under the GNU LGPL license
### The source code for 7-Zip can be found at www.7-zip.org
##
## XCrypt Command Line Reference

## Usage
```
Encrypt: xcrypt e/encrypt [OutputFileName] -p <password> [file/dir name(s)...]
Decrypt: xcrypt d/decrypt [InputFileName] -p <password> [output path:optional]
```

## Command Line Arguments:
```
e/encrypt [OutputFileName]: Encrypt files or directories to specified file
d/decrypt [InputFileName]: Decrypt specified .ENC file
-p/--password: Password used for encryption
```