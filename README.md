## Group Members : 

Anette Ulrichsen

Brandon Nguyen

Farid Aalam

Georden Grabuskie

John Margis

## How to Execute:

To sign:

```python signer.py privKey.pem signature.sig input.txt sign```

privKay.pem = private key
signature.sig = signature
input.txt = file that you want signed
sign = identifier indicating the program to sign 

To verify:

```python signer.py pubKey.pem signature.sig input.txt verify```

privKay.pem = private key
signature.sig = signature
input.txt = file that you want signed
verify = identifier indicating the program to verify 

## Disclaimer:

This is using python 2.7.16