# Order statuses

Both the site and the bot show the same stages. The exchange's own word for its stage is shown beside them for support conversations.

## The normal path

- **Waiting for your deposit.** The order is open and the deposit address is live. Nothing has arrived yet.

- **Confirming on chain.** Your deposit was seen and is gathering confirmations.

- **Exchanging.** The exchange has your deposit and is swapping it. In Privacy mode this covers the hop to the second exchange.

- **Sending to you.** The payout is on its way to your receiving address.

- **Complete.** Paid. The receipt shows what arrived, the payout transaction and the exchange order id. Keep it: it is the only record Shield shows you.

## The other paths

- **The exchange has paused this swap.** The exchange wants to check the deposit before paying out, usually identification or source of funds. Shield names the exchange and links its order page. Only the exchange can release it.

- **The exchange is refunding this deposit.** It needs an address on the network you sent from. Give it one on the exchange's order page.

- **The exchange refunded your deposit.** Funds went back. Nothing was exchanged.

- **The exchange reports a failure.** Contact the exchange with the order id. Do not send anything else to the deposit address.

- **This order expired.** No deposit arrived within the deposit window and the address was closed. Start again.

- **Checking with the exchange.** The exchange reported a word Shield does not recognise yet. It updates by itself.
