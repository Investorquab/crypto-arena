# ⬡ Crypto Arena — BTC Prediction Battle

Multiplayer BTC price prediction game on GenLayer. Up to 8 players compete in real-time — predict if BTC goes UP or DOWN. Last player standing wins, result recorded on-chain by AI consensus.

**Live Demo:** https://crypto-arena.netlify.app
**GitHub:** https://github.com/Investorquab/crypto-arena

## How to Play
1. Create a room or join with a 4-letter code
2. Host clicks START when everyone is ready
3. Each round: 7 seconds to bet BUY or SELL on BTC
4. Watch BTC live price for 15 seconds
5. Wrong call = lose a life ❤️ (2 lives each)
6. Last player standing wins — recorded on GenLayer!

## Tech Stack
- WebSockets — real-time multiplayer
- Binance API — live BTC price every 2 seconds
- GenLayer — winner recorded on-chain by AI consensus
- Canvas chart — live BTC price visualization

## GenLayer Contract
- `record_winner(room, winner, rounds, players)` — records game result via AI consensus
- `get_game(room_code)` — read stored game result
- `get_wins(player)` — player win count
- `get_stats()` — oracle statistics

Built for the GenLayer contribution program.
Deployer: 0xcD7f401774D579B16CEBc5e52550E245d6D88420
