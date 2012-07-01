# coddie 
    Easily encrypt/decrypt files on the fly with a very strong algorithm

## Usage
    coddie [-d] {-a 1|2|3} {-h 1|2|3} [FILE]...

## Options
    -e      Encrypt [FILE] (default)
    -d      Decrypt [FILE]
    -a N    Sets the level of AES algorithm used for encrypt/decrypt [FILE]:
              1 - weak (default), 2 - normal, 3 - strong
    -h N    Sets the level of SHA algorithm used for compute the password's
              checksum: 1 - weak (default), 2 - normal, 3 - strong

## Examples
    Encrypt foo.txt with defaults settings
      coddie foo.txt

    Decrypt foo.enc
      coddie -d foo.txt

## WARNING
    Be sure to remember the settings you use to encrypt a file because without them you're not able to decrypt it back!