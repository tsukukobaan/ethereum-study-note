# Ethereum / Solidityを勉強するためのNote
Blockchain技術(Ethereum/solidity開発)を学ぶドキュメントをまとめるメモです

## 目次

## 学習ロードマップ
ブロックチェーン基礎の学習
Ethereumの学習
環境設定
Tools&Framework

## 情報まとめサイト
[block-chain.jp](http://block-chain.jp/)

## Blockchain基礎まとめ
[Whitepaper by Satoshi Nakamoto](https://bitcoin.org/bitcoin.pdf)\
[Bitcoin.org](https://bitcoin.org/en/)

[Mastering Bitcoin(PDF)](https://www.bitcoinbook.info/translations-of-mastering-bitcoin/)\
[Mastering Bitcoin(HTML)](http://chimera.labs.oreilly.com/books/1234000001802/index.html)

[Coursera:cryptocurrency](https://www.coursera.org/learn/cryptocurrency)\
[Pluralsight:blockchain-fundamentals](https://www.pluralsight.com/courses/blockchain-fundamentals)\
[Pluralsight:bitcoin-decentralized-technology](https://www.pluralsight.com/courses/bitcoin-decentralized-technology)

[Learn blockchains by building one](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46)[(日本語)](https://qiita.com/hidehiro98/items/841ece65d896aeaa8a2a?utm_source=Qiita%E3%83%8B%E3%83%A5%E3%83%BC%E3%82%B9&utm_campaign=8b482bbf74-Qiita_newsletter_282_10_18_2017&utm_medium=email&utm_term=0_e44feaa081-8b482bbf74-32916393)

## Ethereum基礎まとめ
[技術者向け Ethereumの基礎知識 (イーサリアム、エセリウム)](http://block-chain.jp/tech/ethereum-basics-for-engineer/)\
[Ethereum入門](https://www.gitbook.com/book/a-mitani/mastering-ethereum/details)\
[A 101 Noob Intro to Programming Smart Contracts on Ethereum](https://medium.com/@ConsenSys/a-101-noob-intro-to-programming-smart-contracts-on-ethereum-695d15c1dab4)\
[Ethereum Frontier](https://ethereum.gitbooks.io/frontier-guide/content/index.html)\
[Building a smart contract using the command line](https://www.ethereum.org/greeter)\
[Ethereum Clockup memo](http://ethereum.clock-up.jp/)

[Ethereum Stack Exchange](https://ethereum.stackexchange.com/)\
[Ether Scan](https://etherscan.io/)\
[How to setup local test Ethereum Blockchain](https://lightrains.com/blogs/setup-local-ethereum-blockchain-private-testnet)\


## Ethereum
### [Ethereum.org](https://ethereum.org/)
### [Ethereum公式github](https://github.com/ethereum)
 * [web3.js](https://github.com/ethereum/web3.js/)
    Ethereum互換のJavascriptAPI
 * [geth](https://github.com/ethereum/go-ethereum)　wikiが詳しいので読み込むべし
 * [cpp-ethereum](https://github.com/ethereum/cpp-ethereum)
 
[EIP](https://github.com/ethereum/EIPs)\
[testrpc](https://github.com/ethereumjs/testrpc)

　## Solidity
[Solidity](https://github.com/ethereum/solidity)\
[Solidityドキュメンテーション](https://solidity.readthedocs.io/en/develop/)
### Tutorials
[Monax Smart Contract Tutorial](https://monax.io/docs/tutorials/solidity/)\
[Solidity Workshop](https://github.com/androlo/solidity-workshop)\
[Upgradable Contracts](https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88)\
[EthereumDev.io](https://ethereumdev.io/)

web3の他言語実装
[python: Web3.py](https://github.com/pipermerriam/web3.py)\
[haskell: hs-web3](https://github.com/airalab/hs-web3)\
[Java: web3j](https://github.com/web3j/web3j)

## framework
[open-zeppelin](https://openzeppelin.org/)\
[tutorial](https://blog.zeppelin.solutions/the-hitchhikers-guide-to-smart-contracts-in-ethereum-848f08001f05)

[embark](https://github.com/iurimatias/embark-framework)

[Solidityまとめ](https://github.com/bkrem/awesome-solidity)


#### 参考になる実装例
[Solidity By Example](http://solidity.readthedocs.io/en/latest/solidity-by-example.html)\
[solidity-examples](https://github.com/chriseth/solidity-examples)\
[Solidity idiosyncrasies](https://github.com/miguelmota/solidity-idiosyncrasies)\
[Solidity Baby Steps](https://github.com/fivedogit/solidity-baby-steps)\
[DigixDAO contracts](https://github.com/DigixGlobal/digixdao-contracts/tree/master/contracts)\
[hello-doug](https://github.com/monax/hello-doug)\
[slockit/smart-contract](https://github.com/slockit/smart-contract)

## Libraries
[dapp-bin](https://github.com/ethereum/dapp-bin)\
[dappsys](https://github.com/nexusdev/dappsys)\
[instant-dapp-ide](https://github.com/dominicwilliams/instant-dapp-ide)\
[Majoolr Libraries](https://github.com/Majoolr/ethereum-libraries)\
[Solidity Collections](https://github.com/ethereum/wiki/wiki/Solidity-Collections)\
[Solidity Standard Library](https://github.com/ethereum/wiki/blob/master/Solidity-standard-library.md)\
[sqlsol](https://github.com/monax/sqlsol)\
[Truffle](https://github.com/ConsenSys/truffle)


## Tools
[REPL](https://github.com/raineorshine/solidity-repl)\
[solgraph](https://github.com/raineorshine/solgraph)\
[Online Compiler](https://ethereum.github.io/browser-solidity/#version=soljson-latest.js)

#### JavaScript
[solc-js](https://github.com/ethereum/solc-js)\
[solidity-parser](https://github.com/ConsenSys/solidity-parser)\
[sulk](https://github.com/lukehedger/sulk)

#### Utility
[solhint](https://github.com/tokenhouse/solhint)\
[sol-tester](https://github.com/androlo/sol-tester)\
[solcover](https://github.com/JoinColony/solcover)\
[ethrain](https://github.com/sebs/ethrain)\
[rpc-check](https://github.com/sebs/rpc-check)

#### Webpack
[solidity-loader](https://github.com/jeffscottward/solidity-loader)

## Editor Plugins
#### Vim
[vim-solidity](https://github.com/tomlion/vim-solidity)

#### Atom
[autocomplete-solidity](https://atom.io/packages/autocomplete-solidity)\
[language-ethereum](https://atom.io/packages/language-ethereum)\
[linter-solidity](https://atom.io/packages/linter-solidity)

#### Sublime
[SublimeEthereum](https://github.com/davidhq/SublimeEthereum)

#### Emacs
[emacs-solidity](https://github.com/ethereum/emacs-solidity)

#### Visual Studio
[vscode-solidity](https://github.com/juanfranblanco/vscode-solidity)

