# Chapter 2 — Safer practices for USDT payments

Crypto transfers typically cannot be cancelled after confirmation. The absence of ordinary payment chargebacks makes careful verification especially important before moving stablecoins.

## Risks to address before paying

### 1. Mismatched networks

A wallet or exchange might support USDT on one chain but not another. Check both ends of the transfer for the exact blockchain: TRC20, ERC20, or BEP20. Refer to **[Chapter 1](01-networks.md)** for the differences.

### 2. Incorrect or substituted addresses

- Obtain recipient details from a trusted communication channel.
- Use copy-and-paste or QR codes, but verify the address after pasting; malware can replace clipboard contents.
- Do not rely only on the first and last characters. Address-poisoning attacks can imitate them; compare the complete destination using a trusted source.
- Consider a small test transaction for new destinations or substantial amounts, taking fees into account.

### 3. Fraudulent websites and impersonators

- Access wallets and payment providers through verified bookmarks or independently checked domains.
- Treat unexpected direct messages claiming to be support as suspicious.
- Never reveal a recovery phrase or private key. Legitimate support teams do not need either.

### 4. Wallet compromise or lost recovery information

- Keep recovery phrases offline and protected from unauthorized access.
- Consider a hardware wallet for meaningful holdings and independently verify transaction details on its trusted display when supported.
- Use separate wallets when that limits exposure, and protect any custodial account with strong authentication.

## Checklist before a transfer

- [ ] The intended USDT asset and blockchain are supported by both parties
- [ ] The recipient's address was obtained and verified through a trustworthy channel
- [ ] The correct network is selected in the sending service
- [ ] The exact destination and amount have been reviewed
- [ ] Any test transfer is credited before the remainder is sent
- [ ] The recipient or platform has been checked for legitimacy
- [ ] The invoice, date, transaction ID, and related fee records will be retained

## Responding to a mistake or suspected compromise

**Wrong address or unsupported network:** Once confirmed, blockchain transactions are generally irreversible. Contact the receiving platform promptly if it controls the address; some services offer limited recovery assistance, but results are not assured. Be cautious of third parties promising guaranteed recovery.

**Possible account or wallet compromise:** Stop interacting with suspicious links, secure associated accounts, and seek trusted wallet-specific security guidance. If a recovery phrase is exposed, consider moving remaining assets to a newly created wallet using a secure device.

## Review processes and their limits

A withdrawal review can sometimes catch suspicious or inconsistent recipient details before a payment is sent. However, manual or automated review does not guarantee that an address belongs to the correct recipient or that transferred funds can be recovered. When using [FlowPayroll](https://flowpayroll.net) or another payout provider, confirm its current verification and withdrawal procedures directly.

---

Next: **[Chapter 3 — Converting USDT to local currency](03-cashing-out.md)**.

*General educational guidance, not individualized security or financial advice.*
