# Openssl - WIP

## Generate certificate

### Certificate location

```
-v $(pwd):/ssl
```

### Environment variables

Variable          | Default   | Description
----------------- | --------- | ------------------------
`CERT_NAME`       | crt       | certificate name
`OPENSSL_DAYS`    | 365       | req `-days` flag
`OPENSSL_NEWKEY`  | rsa:2048  | req `-newkey` flag
`OPENSSL_SUBJ_C`  | -         | part of req `-subj` flag
`OPENSSL_SUBJ_ST` | -         | part of req `-subj` flag
`OPENSSL_SUBJ_L`  | -         | part of req `-subj` flag
`OPENSSL_SUBJ_O`  | -         | part of req `-subj` flag
`OPENSSL_SUBJ_OU` | -         | part of req `-subj` flag
`OPENSSL_SUBJ_CN` | localhost | part of req `-subj` flag
