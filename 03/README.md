# Nervos 03

This write-up relates to the third challenge. After the smart contract was
delivered, we could make some calls to its `get` and `set` methods. This was
accomplished by modifying the given `index.js` file as pointed out in the
instructions.

Then, we run the script and obtain the result:

# Requisite 1 (Screenshot)

<img src="https://raw.githubusercontent.com/sisco0/nervos-hackathon/main/03/SmartContract_Call.png">

# Requisite 2 (Text)

Transaction Hash:

```
0xb904a8cd76ebb6899424e94ca965a6e8342eda203a1a74f5796343bb89d10b98
```

# Requisite 3 (Text)

Contract address:

```
0x2cdC6a1b5b6659Ca90B83d15558A25Bb729D3E6E
```

# Requisite 4 (Text)

ABI for contract:

```javascript
const CONTRACT_ABI = [{
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
]; // this should be an Array []
```
