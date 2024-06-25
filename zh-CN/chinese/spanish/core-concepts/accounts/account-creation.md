# Account Creation

New accounts are created on the Hedera ledger by submitting a transaction to the network and paying the transaction fee to create the account. The transaction fee to create the account includes the costs required to use network resources, reach consensus amongst the nodes, and share the data across the network.

You will need access to an existing account with enough HBAR to cover the transaction fee to create the account. Suppose you don't have access to an existing account. In that case, you can use a supported wallet or visit the [Hedera Developer Portal](https://portal.hedera.com/register) to create an account. You can also ask a friend with an existing Hedera account to generously create one for you. Applications can check out the "[Auto Account Creation](auto-account-creation.md)" feature to make free Hedera user accounts.

When an account is created, it is stored in the state on the Hedera network. The current state can be queried from the ledger and viewed in a [Network Explorer](../../networks/community-mirror-nodes.md). Each account has at least one public and private key pair. The private key(s) on the account is used to sign and authorize transactions that involve the account. To view the properties that can be set for an account, check out the "[Account Properties](account-properties.md)" section.

An account can be created through any of the following methods. To create accounts using the SDKs, you will need access to an existing account to pay for the transaction fee to create a new account.

{% hint style="warning" %}
:large\_orange\_diamond: Supported wallets may or may not support creating testnet and previewnet accounts.
{% endhint %}

<table data-view="cards"><thead><tr><th align="center"></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center"><strong>Hedera Developer Portal</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="274c">❌</span> mainnet<br><span data-gb-custom-inline data-tag="emoji" data-code="2705">✅</span> testnet<br><span data-gb-custom-inline data-tag="emoji" data-code="2705">✅</span> previewnet</td><td><a href="https://portal.hedera.com/">https://portal.hedera.com/</a></td></tr><tr><td align="center"><strong>Wallets</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2705">✅</span> mainnet<br><span data-gb-custom-inline data-tag="emoji" data-code="1f536">🔶</span> testnet<br><span data-gb-custom-inline data-tag="emoji" data-code="1f536">🔶</span> previewnet</td><td><a href="../../networks/mainnet/mainnet-access.md">mainnet-access.md</a></td></tr><tr><td align="center"><strong>SDKs</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2705">✅</span> mainnet<br><span data-gb-custom-inline data-tag="emoji" data-code="2705">✅</span> testnet<br><span data-gb-custom-inline data-tag="emoji" data-code="2705">✅</span> previewnet<br></td><td><a href="../../sdks-and-apis/deprecated/sdks/cryptocurrency/">cryptocurrency</a></td></tr></tbody></table>