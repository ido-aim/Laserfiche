# CA self gen with open SSL

`openssl genrsa -out private.pem 1024`

# create public key

`openssl rsa -in private.pem -out public.pem -outform PEM -pubout`

# create hash

```
echo 'data to sign' > example.txt

openssl dgst -sha256 < example.txt > example.sha256
```

# sign PKCS1.5 <padding><metadata><hash of input>

`openssl dgst -sha256 -sign private.pem -out example.sha256 example.txt`

# verify

`openssl dgst -sha256 -verify public.pem -signature example.sha256 example.txt`