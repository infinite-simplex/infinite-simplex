# infinite-simplex

I build exchange and market-clearing systems in C++.

**[Infinite Labs](https://infinite-simplex.github.io/InfiniteLabs/)** has the design write-ups, tradeoffs and measurements for everything below.

## Projects

- **[DisruptorExchange](https://github.com/infinite-simplex/DisruptorExchange)**: a Disruptor-style exchange core with lock-free rings, a sequenced gateway, and replicated, leader-elected matching. [Write-up](https://infinite-simplex.github.io/InfiniteLabs/#DisruptorExchangeCore)
- **[EventContractLOB](https://github.com/infinite-simplex/EventContractLOB)**: a limit order book for event contracts, speaking NASDAQ OUCH 4.2, built on DisruptorExchange. [Write-up](https://infinite-simplex.github.io/InfiniteLabs/#EventContractLOB)
- **[BatchGPU](https://github.com/infinite-simplex/BatchGPU)**: an hourly batch auction for GPU compute, cleared by integer network simplex. [Write-up](https://infinite-simplex.github.io/InfiniteLabs/#BatchGPU)
