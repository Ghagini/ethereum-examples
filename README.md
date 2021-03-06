## __Oraclize Ethereum Examples__ [![Join the chat at https://gitter.im/oraclize/ethereum-api](https://badges.gitter.im/Join%21Chat.svg)](https://gitter.im/oraclize/ethereum-api?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Docs@Oraclize.it](https://camo.githubusercontent.com/5e89710c6ae9ce0da822eec138ee1a2f08b34453/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f63732d536c6174652d627269676874677265656e2e737667)](http://docs.oraclize.it) [![Contributions Welcome!](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/oraclize/ethereum-examples/issues) [![HitCount](http://hits.dwyl.io/oraclize/ethereum-examples.svg)](http://hits.dwyl.io/oraclize/ethereum-examples)

Here you can find some code examples showing just how __easy__ it is to integrate the __Oraclize__ Service into your Ethereum smart-contracts! Thanks to our [__Ethereum API__](https://github.com/oraclize/ethereum-api) using __Oraclize__ in your projects couldn't be more straightforward. In Solidity it is as simple as inheriting the __`usingOraclize`__ contract like so:

```
    contract YourSmartContract is usingOraclize {
        // … 
    }
```

This provisions your contract with the __`oraclize_query()`__ function (and many others!), which makes it trivial to leverage our technology straight away. Head into the __`Solidity`__ directory for more information.

:computer: Happy developing!

***

### __Serpent__

:skull: __CAUTION__: It is highly recommended to avoid using Serpent, especially in production. The examples herein have been left for historical reasons but support for it is no longer maintained as. Serpent is considered outdated and audits have shown it to be flawed. Use them at your own risk!
