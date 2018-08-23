A node.js library to create text qr code.

## Install

$ npm install text-qrcode

## Usage

var qrcode = require('text-qrcode');

var text = qrcode.generate('test qr code');

console.log(text);
