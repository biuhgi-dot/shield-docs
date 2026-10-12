# How it works

## A price from every exchange, the cheapest takes the swap

Shield is connected to several independent cryptocurrency exchanges. When you ask for a swap, each is asked for its price at your exact amount. The cheapest one that can take the swap gets it, and you see the deposit details at once. There is no list to choose from and no exchange name to remember: Shield's job is to find the best price every time.

## Shield never holds your funds

The deposit address you are shown belongs to the exchange processing your swap. You send to the exchange, the exchange pays your receiving address from its own wallet. At no point does Shield hold, forward or custody anything. Shield keeps no accounts and asks for no identification.

## Why that is private

On chain, your sending address paid the exchange, and the exchange's wallet paid your receiving address. There is no transaction linking the two. That is one break in the trail, and it is what every mode gives you. Privacy mode does it twice, through two different exchanges on two different networks, so no single exchange sees both ends.

## The price you see

The amount shown before you place an order is the exchange's price at that moment with Shield's fee already inside it. Nothing is added later. Floating prices are set when the deposit lands and can differ slightly from the quote; the receipt shows what actually arrived.

## The deposit window

A deposit address stays open for 90 minutes. Send within that time. An order with no deposit after 90 minutes is closed and the address must not be used: start again for a fresh quote.

## If an exchange pauses a swap

Exchanges screen deposits. Occasionally one pauses a swap to ask for identification or the source of funds. When that happens Shield names the exchange, shows its order id and links to its order page, because that conversation is between you and the exchange. See [order statuses](order-statuses.md).
