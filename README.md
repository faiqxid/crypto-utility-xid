# Crypto Price Converter

A simple npm module to convert cryptocurrency prices between different currencies.

## Installation

npm install crypto-utility-xid


## Usage

```javascript
const { encryptMessage, decryptMessage } = require('crypto-utility-xid');

const message = 'Hello, world!';
const key = 'secret key';

const encryptedMessage = encryptMessage(message, key);
console.log('Encrypted:', encryptedMessage);

const decryptedMessage = decryptMessage(encryptedMessage, key);
console.log('Decrypted:', decryptedMessage);
