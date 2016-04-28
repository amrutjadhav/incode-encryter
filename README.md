# incode-encryter
When we are writting notes, important data, journals we write it as a simple text. It is not exposed to other account. But if someone open your account he/she can read your personal files, notes etc. 
Incode encrypter is a google chrome extension which can be used to encrypt your text so that you can be relax. Just input what you want to write on online platform and it will encrypt it. Then the resultant encrypted code can be uploaded to online platforms. When you want your original text just copy-paste your encrypted text from online platform and extension will give you your original text back. This way online platforms, companies will not understand what you have written because all it is encrypted and you can preserve your security. It is “Best way to secure your secured data”. 

#### crypto-js

CryptoJS is a growing collection of standard and secure cryptographic algorithms implemented in JavaScript using best practices and patterns. They are fast, and they have a consistent and simple interface.

###### The Hasher Algorithm : MD5 

```javascript
	var hash = CryptoJS.MD5("Message");
```
###### The Cipher Algorithms : AES 

```javascript
	var encrypted = CryptoJS.AES.encrypt("Message", "Secret Passphrase"); 
	var decrypted = CryptoJS.AES.decrypt(encrypted, "Secret Passphrase");
```

