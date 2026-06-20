# TradeGame MVP Demo

**Live Demo:** Open `index.html` in your browser to start trading!

## What This Is

A fully functional paper trading simulator MVP that demonstrates the core TradeGame concept:
- **Three markets:** Crypto (BTC-SIM), Stocks (TECH-SIM), Forex (EUR/USD-SIM)
- **Real-time scenario playback:** Watch simulated market data tick by tick
- **Position management:** Open long/short positions with stop loss and take profit
- **Risk calculator:** See your risk exposure before entering trades
- **Trade journal:** Track all your trades with P&L

## Features Implemented

✅ **Market Selection** - Choose between crypto, stocks, or forex  
✅ **Live Price Charts** - Canvas-based real-time price visualization  
✅ **Paper Trading** - $10,000 starting balance, simulated positions  
✅ **Risk Management** - Mandatory stop loss / take profit on every position  
✅ **Position Sizing** - Calculate risk before entering trades  
✅ **Trade Journal** - Track all your trades with P&L  
✅ **Educational Focus** - Prominent disclaimers, process over profit  
✅ **Teaching Mode** - $1,000 challenge mode to learn strict risk limits  

## How to Use

1. **Open `index.html`** in any modern browser (Chrome, Firefox, Safari, Edge)
2. **Choose a market** - Click Crypto, Stocks, or Forex
3. **Watch the scenario play** - Prices update automatically
4. **Set your position** - Choose size, stop loss, and take profit
5. **Enter a trade** - Click Buy/Long or Sell/Short
6. **Monitor your position** - Watch P&L update in real-time
7. **Close or let it auto-close** - Stop loss/take profit execute automatically

## Educational Design

This MVP emphasizes **process over profit**:
- Risk calculator shows exposure before trading
- Stop losses are mandatory (can't be disabled)
- Trade journal logs ALL trades, wins and losses
- Prominent disclaimers throughout
- No gambling mechanics or loot boxes

## Technical Stack

- **Pure HTML/CSS/JavaScript** - No frameworks, no build step
- **Canvas API** - For chart rendering
- **Responsive design** - Works on desktop and mobile
- **Local storage ready** - Can be extended to save progress

## Next Steps for Full Version

- [ ] Add more scenario types (trending, ranging, volatile)
- [ ] Implement historical scenario replays (famous market moments)
- [ ] Add strategy sandboxes (grid bots, DCA simulators)
- [ ] Create progression system (unlock features with good process)
- [ ] Add coaching feedback system
- [ ] Implement community features (leaderboards, peer review)
- [ ] Add journaling prompts and trade analysis
- [ ] Create tutorial system for new users

## Deployment

### GitHub Pages (Recommended)
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Set source to `main` branch, `/demo` folder
4. Access at `https://yourusername.github.io/TradeGame---Preview/demo/`

### Local Testing
Simply open `index.html` in your browser - no server required!

### Custom Domain
After GitHub Pages is enabled, add a CNAME file with your domain.

## Disclaimers

⚠️ **IMPORTANT:** This is an educational simulator only. Nothing here constitutes financial advice. All instruments and prices are entirely fictional and simulated. Trading involves risk of significant loss. Consult a licensed financial professional before any real trading.

## License

Proprietary - See [LICENSE](../LICENSE)

---

**Built with the Autonomous Work Framework** 🚀  
*Created: 2026-06-20*