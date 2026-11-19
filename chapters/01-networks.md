# Chapter 1 — Choosing between TRC20, ERC20, and BEP20

USDT is offered across multiple blockchains. The label **USDT** does not by itself identify the network used to send it. Each network has its own transaction mechanics, fee requirements, and service compatibility. Understanding those differences helps prevent costly deposits to unsupported destinations.

## Three commonly encountered networks

### TRC20: USDT on Tron

- **Network fees:** Tron uses bandwidth and energy resources; when resources are insufficient, TRX may be burned to pay for the transaction. Costs can vary substantially.
- **Settlement:** Transfers may appear quickly, but recipient platforms can require additional confirmations or checks before crediting them.
- **Common use:** Cross-border USDT transfers when both providers support Tron.
- **Address pattern:** Tron addresses commonly begin with `T`.

### BEP20: USDT on BNB Smart Chain

- **Network fees:** Transactions ordinarily consume BNB for gas.
- **Settlement:** Confirmation and platform crediting times depend on network and service rules.
- **Common use:** Payments involving providers or wallets that support BNB Smart Chain.
- **Address pattern:** Uses `0x`-prefixed addresses.

### ERC20: USDT on Ethereum

- **Network fees:** Ethereum transactions require ETH for gas, with costs changing according to network activity.
- **Settlement:** The blockchain and receiving institution determine how quickly the payment becomes usable.
- **Common use:** Ethereum-compatible wallets, exchanges, and applications.
- **Address pattern:** Also uses `0x`-prefixed addresses.

> **Same address format, different networks.** ERC20 and BEP20 addresses can look identical. Always check which *blockchain* the recipient accepts, not simply whether the address looks valid.

## At-a-glance reference

| Detail | TRC20 | BEP20 | ERC20 |
|---|---|---|---|
| Blockchain | Tron | BNB Smart Chain | Ethereum |
| Gas / resource requirement | Tron resources or TRX | BNB | ETH |
| Typical address style | `T...` | `0x...` | `0x...` |
| Fee level | Resource-dependent | Generally low, variable | Variable, sometimes higher |
| Key check | Tron deposit supported | BNB Smart Chain deposit supported | Ethereum deposit supported |

## Select a network safely

1. **Start with the recipient.** Check that the wallet, exchange, or provider explicitly supports receiving your particular USDT asset on the intended network.
2. **Confirm sender compatibility.** Make sure the sender can withdraw or transfer on that same network.
3. **Compare total transaction cost.** Review live gas/resource requirements and any platform-specific fees.
4. **Inspect the deposit instructions.** Follow provider requirements such as minimum deposits or transaction confirmations.
5. **Test when appropriate.** An initial small transfer can help confirm the route before a larger transaction, although it cannot eliminate all risk.

## Final network check

Before submitting any transfer, confirm the **token**, **blockchain**, **recipient address**, and **amount**. Sending funds through an unsupported chain can result in funds that cannot be accessed or recovered.

---

Continue to **[Chapter 2: transfer safety](02-safety.md)**.

*Information is educational and network conditions change.*
