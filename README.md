# CryptoBuddy: Sustainable Cryptocurrency Recommendation Bot

CryptoBuddy is a simple Python chatbot that helps users learn about the sustainability and eco-friendliness of popular cryptocurrencies. The bot provides recommendations based on sustainability score, energy use, market capitalization, and price trends for Bitcoin, Ethereum, and Cardano.

## Features

- **Sustainability Guidance:** Recommends the most eco-friendly cryptocurrency.
- **Energy Use Insights:** Shares which cryptocurrency is best in terms of energy consumption.
- **Market Cap Recommendations:** Highlights the crypto with the highest market capitalization.
- **Price Trend Advice:** Suggests a cryptocurrency with the best current price trend.
- **Conversational Loop:** Keeps chatting until the user types "quit", "exit", or "bye".

## How It Works

The core data is stored in a dictionary named `responses`, which contains key metrics for each cryptocurrency:
- `price_trend`: Current trend (e.g., "rising", "stable")
- `market_cap`: Market capitalization ("high", "medium")
- `energy_use`: Energy consumption level ("high", "medium", "low")
- `sustainability_score`: A numerical score (out of 10) reflecting environmental friendliness

The function `get_bot_response(user_input)` analyzes the user's input and responds with the best recommendation based on their query.

## Usage

1. **Clone or copy the code.**
2. **Run the script with Python 3:**
   ```bash
   python script.py
   ```
3. **Interact with CryptoBuddy:**
   - Ask about sustainability, market cap, energy use, or price trends.
   - Type "quit", "exit", or "bye" to end the session.

### Example Conversation

```
You: Which coin is the most sustainable?
cryptobuddy: Invest in Cardano! 🌱 It’s eco-friendly and has long-term potential!

You: What about market cap?
cryptobuddy: Invest in Bitcoin! 🌱 It’s eco-friendly and has long-term potential

You: bye
Bot: Goodbye! If you have any more questions, we're here to help.
```

## Customization

- **Add More Cryptocurrencies:** Extend the `responses` dictionary with new entries.
- **Adjust Scoring:** Update the values for trends, cap, energy use, and sustainability to reflect current research or data.

## Disclaimer

CryptoBuddy is a demo for educational purposes and does not constitute investment advice. Cryptocurrency data is hard-coded and may not reflect real-time market or sustainability metrics.

---

*Happy sustainable investing! 🌿*
