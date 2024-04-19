# 虫洞跨链桥使用指南

### 免责声明&#x20;

在开始使用虫洞跨链桥之前，请务必阅读本指南。

本指南将分步解释如何使用虫洞跨链桥，并演示了其可以立即使用的一些好用的功能，如 translation searching 和 transaction resuming。本指南还提供了操作指引协助自助排除常见故障。

### 使用跨链桥的操作步骤

<figure><img src="../../.gitbook/assets/image (387).png" alt=""><figcaption></figcaption></figure>

1. **前往 PancakeSwap 虫洞跨链桥页面** - [https://bridge.pancakeswap.finance/wormhole](https://bridge.pancakeswap.finance/wormhole)&#x20;
2. **连接原链钱包** - 第一步是连接钱包。使用插件钱包时，无需将钱包手动切换为您要跨出资产的网络。虫洞会根据您选择的网络自动切换到正确的网络。当原链为 EVM 链时，仅支持使用 Metamask。
3. **选择原链网路** - PancakeSwap 目前通过虫洞跨链桥支持 4 个网络（以太坊主网、币安智能链、Arbitrum 和 Base）。&#x20;
4. **选择原链资产** - 选择要跨链的代币。&#x20;
5. **在步骤 4、5 和 6** - 在目标链栏位，重复步骤 1、2 和 3&#x20;
6. **输入跨链金额** - 输入跨链金额，然后进行授权链上操作。路径和跨链细节将显示如下：

<figure><img src="../../.gitbook/assets/image (388).png" alt="" width="563"><figcaption></figcaption></figure>

7. 一旦授权完成，并发送链上交易，就会显示此链上交易状态页面：

<figure><img src="../../.gitbook/assets/image (389).png" alt="" width="563"><figcaption></figcaption></figure>

跨链有三个步骤。这些步骤可能需要一些时间，通常需要对原链上的链上交易进行一定数量的区块确认。一旦达到这个确认阈值。虫洞就会生成证明，确认链上交易成功。需要该证明才能在目标链上领取您的跨链资产。&#x20;

8. 一旦验证完成，您就可以通过点击显示的 "Claim (领取）" 按钮来领取您的跨链资产：

<figure><img src="../../.gitbook/assets/image (390).png" alt="" width="563"><figcaption></figcaption></figure>
