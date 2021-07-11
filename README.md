# Go Cypher Librery

## **install**
- ***Generate Key***
   ```go
    go get github.com/Leonardo-Antonio/goCypher
## **how to use**
> se recomienda usar como key de un .env por seguridad
- ***Generate Key***
   ```go
    key := cyhper.CreateHash(<youPassword>)
  ```

- ***Encrypt Data***
   ```go
    encrypt, err := cyhper.Encrypt(<youData>, key)
  ```

- ***Decrypt Data***
   ```go
    decrypt, err := cyhper.Decrypt(<encodedData>, key)
  ```