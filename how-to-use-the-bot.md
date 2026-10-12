# How to use the bot

Open the Shield bot in Telegram and send `/start`. Tap **Agree** once. Then answer the questions with the buttons, or by typing where it asks you to.

## Typing amounts

Type the amount in the coin, for example `0.25`, or in dollars, for example `$50` or `50 usd`. A dollar amount is converted at the current price and the bot tells you what it became. The order is always placed in coin.

## Addresses

Paste your receiving address as a message. In a Split, paste one address per line. For XRP the bot asks for the destination tag after the address. Every address is checked against the exchange's own rules before anything is opened.

## The deposit message

It shows the exact amount to send, the deposit address (tap to copy), a QR code, the deadline, and your Shield order id. Send from a wallet you control, in one payment. Then tap **I've sent it** to start tracking. The tracking message updates by itself until the swap is complete.

## Coming back to an order

Send `/track` followed by the Shield order id from the deposit message, for example `/track 2ef86d33-f7b1-4661-9c1a-0b5e7d3a8f21`. This works in any chat with the bot, including after the bot has restarted.

## Other buttons

**Back** returns to the previous question. **Cancel** forgets an order on Shield's side only; an order you have already paid continues at the exchange. **Start another swap** appears on the receipt.
