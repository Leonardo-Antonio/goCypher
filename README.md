# Go Cypher Librery

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