### Currently working on the LDK node in [ZEUS](https://github.com/ZeusLN/zeus)

**Channel splicing:** add funds to an open channel, or take them out, without closing it.
- [ZeusLN/zeus#4703](https://github.com/ZeusLN/zeus/pull/4703) Splicing for the LDK node and Core Lightning (draft)
- [ZeusLN/ldk-node#15](https://github.com/ZeusLN/ldk-node/pull/15) Splice fee rates and fixes, backported to ZEUS's ldk-node

**LSPS2 just-in-time channels:** receive with no inbound liquidity; the LSP opens a channel as the payment arrives.
- [ZeusLN/zeus#5765](https://github.com/ZeusLN/zeus/pull/5765) LSPS2 JIT channels for the LDK node (draft)

**External accounts:** watch-only xpub accounts (hardware wallets included), with sends signed externally via PSBT.
- [ZeusLN/zeus#4210](https://github.com/ZeusLN/zeus/pull/4210) External accounts for the LDK node (draft)
- [ZeusLN/ldk-node#1](https://github.com/ZeusLN/ldk-node/pull/1) Watch-only on-chain accounts in ldk-node (draft)

**Upstream in [ldk-node](https://github.com/lightningdevkit/ldk-node):**
- [#1223](https://github.com/lightningdevkit/ldk-node/pull/1223) Count the funding fee in the anchor reserve check for splice-ins
- [#1204](https://github.com/lightningdevkit/ldk-node/pull/1204) Count the funding fee in anchor reserve checks for channel opens
