# Bitcoin Wallet Generator
 Script em Node.js com pacotes bit32, bit39 e bitcoinjs-lib. Ele gera uma carteira, chave privada em WIF e endereço público em P2PKH com foco em Bitcoin.

## Installation

```
npm install bip32
npm install bip39
npm install bitcoinjs-lib
```

## code 

```node.js
const bip32 = require("bip32")
const bip39 = require("bip39")
const bitcoin = require("bitcoinjs-lib")


 ___ ___       __ __       __   _______                              __              
|   Y   .---.-|  |  .-----|  |_|   _   .-----.-----.-----.----.---.-|  |_.-----.----.
|.  |   |  _  |  |  |  -__|   _|.  |___|  -__|     |  -__|   _|  _  |   _|  _  |   _|
|. / \  |___._|__|__|_____|____|.  |   |_____|__|__|_____|__| |___._|____|_____|__|  
|:      |                      |:  1   |                                             
|::.|:. |                      |::.. . |                                             
`--- ---'                      `-------'                                             
                                                                                     


       Por: @viniciussouzati | Wallet Generator | 2023 | Project under development
        """))

## Utilização

Esse é um Wallet Generator tester. Para criação muda const path ='m/49/1/0/0' para const path ='m/49/0/0/0'.

Você pode ver visulizar esse test no site "https://blockexplorer.one/bitcoin/testnet". Ao colar a chave do endereço, será possível visualizar todas as moedas e transações. 
 
