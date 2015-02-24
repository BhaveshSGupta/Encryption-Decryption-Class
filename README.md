# Encryption-Decryption-Class
An Php class to work With Encryption and Decryption,

##How to use this class
Way 1: 
```
$cipher = new EDcipher('Bhavesh');
$encrypted = $cipher->encrypt('BhaveshSGupta');
print "Encrypted :".$encrypted."<br>" ;
print "Decrypted :".$cipher->decrypt($encrypted);
```

Output:

```
Encrypted :9COVOn3cbUnqin+Hrwh6KQ==
Decrypted :BhaveshSGupta
```
Way 2:
```
$cipher = new EDcipher('Bhavesh','DES-EDE3-CFB');
$encrypted = $cipher->encrypt('BhaveshSGupta');
print "Encrypted :".$encrypted."<br>" ;
print "Decrypted :".$cipher->decrypt($encrypted);
```

output:
```
Encrypted :hXq94qZmTq+dMTZk8g==
Decrypted :BhaveshSGupta
```
