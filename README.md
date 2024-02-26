# Crypto Utility

A simple npm module for encrypting and decrypting messages using AES encryption.

## Installation

npm install crypto-utility


## Usage

```javascript
const { encryptMessage, decryptMessage } = require('crypto-utility');

const message = 'Hello, world!';
const key = 'secret key';

const encryptedMessage = encryptMessage(message, key);
console.log('Encrypted:', encryptedMessage);

const decryptedMessage = decryptMessage(encryptedMessage, key);
console.log('Decrypted:', decryptedMessage);
