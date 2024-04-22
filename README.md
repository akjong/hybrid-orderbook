# hybrid-orderbook

An intent based trading platform, backed by orderbook and amm dex

## Design

There are two roles in the trading markerplace, traders and liquidity providers.

AMM Dex provides the best experience for liquidity providers, they can just deposit their assets and earn fees, without worrying about the price and amount of the orders.

Traders usually don’t care about their counterparties, so we can use AMM to provide liquidity, and use orderbook to provide price discovery.

The UI is just like an orderbook exchange, but the liquidity is not provided by market maker(of course you can also do that), it’s provided by the AMM, and a relayer service will relay the orders according to the price and amount on orderbook and AMM.

The hybrid orderbook can aggregate AMM and orderbook dex and cex into one single orderbook, and provides a unified orderbook trading experience.A hybrid orderbook which aggregates AMM and orderbook dex and cex into one single orderbook, and provides a unified orderbook trading experience.
