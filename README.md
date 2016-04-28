# incode-encryter
When we are writting notes, important data, journals we write it as a simple text. Data written to google keep is not shown to others but google can read what you write, what your thoughts, your account details, your passwords(If you have written). Because it is plain text, and they can interpret from this. We think our data, passwords is secure but it’s not. Data which is not shown to other people doesn’t mean it never exposed to online platforms. So what to do, to prevent this, What is the best way to secure the secured data?

Incode encrypter is a google chrome extension which can be used to encrypt your text so that you can be relax. Just input what you want to write on online platform and it will encrypt it. Then the resultant encrypted code can be uploaded to online platforms. When you want your original text just copy-paste your encrypted text from online platform and extension will give you your original text back. This way online platforms, companies will not understand what you have written because all it is encrypted and you can preserve your security on your side. It is “Best way to secure your secured data”. 

## crypto-js

CryptoJS is a growing collection of standard and secure cryptographic algorithms implemented in JavaScript using best practices and patterns. They are fast, and they have a consistent and simple interface.

#### The Hasher Algorithm : MD5 

```javascript
	var hash = CryptoJS.MD5("Message");
```
#### The Cipher Algorithms : AES 

```javascript
	var encrypted = CryptoJS.AES.encrypt("Message", "Secret Passphrase"); 
	var decrypted = CryptoJS.AES.decrypt(encrypted, "Secret Passphrase");
```
## To install extension in chrome follow this steps:

1) Download extension zip folder and extract it.<br />
2) Open Google chrome -> Settings -> Extensions. <br />
3) Click "Load unpacked extension" button and select the extracted incode encrypter 	    extension folder. <br />
	Happy Hacking.. :)
