# AIOZ Network Releases

---

## v1.4.0

_Release Date: 2023-04-28_

### Release Notes

This release encompasses updates to the Cosmos SDK, Ethermint, and IBC-go, addressing numerous bug fixes and improvements. Notably, the release introduces the wetx module, enabling the sending of EVM transactions with Cosmos signing. Additionally, the aiozrc20 module now includes an aiozrc20 converter, providing an improved user experience when interacting with the wrapped AIOZRC-20 token. This converter grants EVM access to AIOZ-specific features like IBC and gravity, expanding functionality within the ecosystem.

### Improvements

- (sdk) Update Cosmos SDK version to [v0.46.12](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.46.12).
- (ethermint) Update Ethermint version to [v0.22.0](https://github.com/evmos/ethermint/releases/tag/v0.22.0).
- (ibc) Update IBC-go version to [v6.1.0](https://github.com/cosmos/ibc-go/releases/tag/v6.1.0).
- (gravity) Add a forked version of Gravity Bridge module [v1.8.2](https://github.com/Gravity-Bridge/Gravity-Bridge/releases/tag/v1.8.2).
- (aioz) Add module `wetx`.
- (aioz) Add `aiozrc20 converter`.

### Binaries

&nbsp;&nbsp;▣ [aiozd-v1.4.0-darwin-amd64.tar.gz](https://archive.aioz.network/aiozd-v1.4.0-darwin-amd64.tar.gz)  
&nbsp;&nbsp;▣ [aiozd-v1.4.0-linux-amd64.tar.gz](https://archive.aioz.network/aiozd-v1.4.0-linux-amd64.tar.gz)  
&nbsp;&nbsp;▣ [aiozd-v1.4.0-windows-amd64.zip](https://archive.aioz.network/aiozd-v1.4.0-windows-amd64.zip)

---

## v1.3.0

_Release Date: 2022-12-15_

### Release Notes

This release incorporates several significant upgrades. The Cosmos SDK has been updated to version v0.46, introducing new features such as group, Msg-based governance proposals, PostHandlers, and Transaction Tip support. Additionally, Ethermint has been upgraded to v0.20, bringing numerous improvements to the EVM core and EIP712 support. The IBC-go module has also been updated to v5.1.0, introducing the Fee Middleware module in preparation for future adaptations involving IBC relaying fees. Lastly, the aiozrc20 module has undergone various optimizations and improvements, enhancing its overall performance and functionality.

### Improvements

- (sdk) Update Cosmos SDK version to [v0.46.7](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.46.7).
- (ethermint) Update Ethermint version to [v0.20.0](https://github.com/evmos/ethermint/releases/tag/v0.20.0).
- (ibc) Update IBC-go version to [v5.1.0](https://github.com/cosmos/ibc-go/releases/tag/v5.1.0).
- (aioz) Optimize and improve module aiozrc20.

### Binaries

&nbsp;&nbsp;▣ [aiozd-v1.3.0-darwin-amd64.tar.gz](https://archive.aioz.network/aiozd-v1.3.0-darwin-amd64.tar.gz)  
&nbsp;&nbsp;▣ [aiozd-v1.3.0-linux-amd64.tar.gz](https://archive.aioz.network/aiozd-v1.3.0-linux-amd64.tar.gz)  
&nbsp;&nbsp;▣ [aiozd-v1.3.0-windows-amd64.zip](https://archive.aioz.network/aiozd-v1.3.0-windows-amd64.zip)

---

## v1.2.0

_Release Date: 2022-04-16_

### Release Notes

This release incorporates upgrades to the Cosmos SDK, Tendermint, and Ethermint, introducing various improvements and enhancements. Notably, a patch has been applied to Ethermint to address gas price suggestion issues, ensuring a more accurate and reliable transaction experience. Additionally, the release introduces the aiozrc20 module, laying the groundwork for the automatic conversion of the native coin into AIOZRC-20, enhancing accessibility and expanding utility within the ecosystem.

### Improvements

- (sdk) Update Cosmos SDK version to [v0.45.3](https://github.com/AIOZNetwork/cosmos-sdk/releases/tag/v0.45.3-aioz.1).
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

- (sdk) Update Cosmos SDK version to [v0.44.5](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.44.5).
- (tendermint) Update Tendermint version to [v0.34.14](https://github.com/tendermint/tendermint/releases/tag/v0.34.14).
- (ethermint) Add Ethermint version [v0.9.0](https://github.com/tharsis/ethermint/releases/tag/v0.9.0).
- (aioz) Add module eetx.
- (aioz) Add module bonus.

### Binaries

&nbsp;&nbsp;▣ [aiozd-v1.0.0-darwin-amd64.tar.gz](https://archive.aioz.network/aiozd-v1.0.0-darwin-amd64.tar.gz)  
&nbsp;&nbsp;▣ [aiozd-v1.0.0-linux-amd64.tar.gz](https://archive.aioz.network/aiozd-v1.0.0-linux-amd64.tar.gz)  
&nbsp;&nbsp;▣ [aiozd-v1.0.0-windows-amd64.zip](https://archive.aioz.network/aiozd-v1.0.0-windows-amd64.zip)
