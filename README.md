# apm.js

JavaScript library to interact with the Aragon Package Management protocol.

## Installation

```
npm i @aragon/apm
```

## Usage

TBD.

## Documentation

TBD.

## Testing

Requires IPFS and an Aragon devchain running. IPFS can be started via the IPFS daemon ([install link](https://docs.ipfs.io/how-to/command-line-quick-start/)), the Aragon devchain can be started by running `yarn pretest` in the [aragon-cli](https://github.com/aragon/aragon-cli/tree/master) repo.

To test:

`npm test`

## Usage

After installing the package, you can import and initialize it as follows:

```js
import APM from '@aragon/apm'

// Example: connect to a local Aragon devchain
const apm = new APM('http://localhost:8545')

---

C’est une amélioration mineure, propre et utile, donc parfaite pour une première pull request.  
Tu veux que je t’écrive le titre et la description du PR associés à ça aussi ?
