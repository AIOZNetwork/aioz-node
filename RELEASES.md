# AIOZ Network Releases

---

## v1.2.0

_Release Date: 2022-04-16_

### Release Notes

This release incorporates upgrades to the Cosmos SDK, Tendermint, and Ethermint, introducing various improvements and enhancements. Notably, a patch has been applied to Ethermint to address gas price suggestion issues, ensuring a more accurate and reliable transaction experience. Additionally, the release introduces the aiozrc20 module, laying the groundwork for the automatic conversion of the native coin into AIOZRC-20, enhancing accessibility and expanding utility within the ecosystem.

### Improvements

- (sdk) Update SDK version to [v0.45.3](https://github.com/AIOZNetwork/cosmos-sdk/releases/tag/v0.45.3-aioz.1).
- (tendermint) Update Tendermint version to [v0.34.19](https://github.com/tendermint/tendermint/releases/tag/v0.34.19).
- (ethermint) Update Ethermint version to [v0.13.0](https://github.com/AIOZNetwork/ethermint/releases/tag/v0.13.0-aioz.1).
- (aioz) Add module aiozrc20.
- (bug fixes) Apply a patched version of Ethermint to fix gas price suggestion.

### Binaries

&nbsp;&nbsp;▣ [aiozd-v1.2.0-darwin-amd64.tar.gz](https://archive.aioz.network/aiozd-v1.2.0-darwin-amd64.tar.gz)  
&nbsp;&nbsp;▣ [aiozd-v1.2.0-linux-amd64.tar.gz](https://archive.aioz.network/aiozd-v1.2.0-linux-amd64.tar.gz)  
&nbsp;&nbsp;▣ [aiozd-v1.2.0-windows-amd64.zip](https://archive.aioz.network/aiozd-v1.2.0-windows-amd64.zip)

---

## v1.1.0

_Release Date: 2022-03-23_

### Release Notes

This release introduces significant enhancements, including the addition of Etheremint's EIP712 for EVM transaction signing compatibility with popular wallets like Metamask. With this integration, the need for the eetx module is eliminated, streamlining the process. Furthermore, the update includes performance improvements to the Cosmos SDK, Ethermint, and IBC, optimizing the overall functionality and responsiveness of the node.

### Improvements

- (app) Support Ethermint's EIP712
- (sdk) Update Cosmos SDK version to [v0.45.1](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.45.1).
- (ethermint) Update Ethermint version to [v0.11.0](https://github.com/tharsis/ethermint/releases/tag/v0.11.0).
- (ibc) Update ibc-go version to [v3.0.0](https://github.com/cosmos/ibc-go/releases/tag/v3.0.0).
- (aioz) Remove module eetx.

### Binaries

&nbsp;&nbsp;▣ [aiozd-v1.1.0-darwin-amd64.tar.gz](https://archive.aioz.network/aiozd-v1.1.0-darwin-amd64.tar.gz)  
&nbsp;&nbsp;▣ [aiozd-v1.1.0-linux-amd64.tar.gz](https://archive.aioz.network/aiozd-v1.1.0-linux-amd64.tar.gz)  
&nbsp;&nbsp;▣ [aiozd-v1.1.0-windows-amd64.zip](https://archive.aioz.network/aiozd-v1.1.0-windows-amd64.zip)

---

## v1.0.0

_Release Date: 2021-12-25_

### Improvements

- (sdk) Update SDK version to [v0.44.5](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.44.5).
- (tendermint) Update Tendermint version to [v0.34.14](https://github.com/tendermint/tendermint/releases/tag/v0.34.14).
- (ethermint) Add Ethermint version [v0.9.0](https://github.com/tharsis/ethermint/releases/tag/v0.9.0).
- (aioz) Add module eetx.
- (aioz) Add module bonus.

### Binaries

&nbsp;&nbsp;▣ [aiozd-v1.0.0-darwin-amd64.tar.gz](https://archive.aioz.network/aiozd-v1.0.0-darwin-amd64.tar.gz)  
&nbsp;&nbsp;▣ [aiozd-v1.0.0-linux-amd64.tar.gz](https://archive.aioz.network/aiozd-v1.0.0-linux-amd64.tar.gz)  
&nbsp;&nbsp;▣ [aiozd-v1.0.0-windows-amd64.zip](https://archive.aioz.network/aiozd-v1.0.0-windows-amd64.zip)
