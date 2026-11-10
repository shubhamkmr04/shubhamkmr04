### 🔨 Currently working on: Lightning channel splicing for the embedded LDK node and Core Lightning at [@ZeusLN](https://github.com/ZeusLN)

Splicing adds funds to an open Lightning channel, or takes funds out of it, without closing it.

- **ZEUS:** [ZeusLN/zeus#4703](https://github.com/ZeusLN/zeus/pull/4703) (draft)
- **Upstream in ldk-node:**
  - ✅ [#1159](https://github.com/lightningdevkit/ldk-node/pull/1159) Allow specifying a fee rate when splicing
  - 🔄 [#1223](https://github.com/lightningdevkit/ldk-node/pull/1223) Count the funding fee in the anchor reserve check for splice-ins
  - 🔄 [#1204](https://github.com/lightningdevkit/ldk-node/pull/1204) Count the funding fee in anchor reserve checks for channel opens

### 🔜 Up next: external accounts for the LDK node

Watch-only accounts for ZEUS's embedded LDK node: import an xpub (hardware wallets included), receive, and send with externally signed PSBTs.

- **ZEUS:** [ZeusLN/zeus#4210](https://github.com/ZeusLN/zeus/pull/4210)
- **ldk-node fork:** [ZeusLN/ldk-node#1](https://github.com/ZeusLN/ldk-node/pull/1)
