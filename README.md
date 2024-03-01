# RandomID Generator

## Description

The RandomID Generator is a Node.js module designed to generate random alphanumeric IDs of a specified length.

## Installation

You can install the RandomID Generator via npm using the following command:

```bash
npm install @natalialasz/randomid-generator
```
## Usage

Below is an example demonstrating how to use the RandomID Generator package:

```javascript
const randomID = require('@natalialasz/randomid-generator');

// Generate an identifier with a length of 10
const id = randomID(10);
console.log(id); // It will display a random identifier with a length of 10