# Klacrt Crypto Assistant

Klacrt is an AI-powered cryptocurrency assistant application built with Streamlit and LangChain that provides real-time information about cryptocurrency prices, market data, and answers crypto-related questions.

## Features

- **Real-time Cryptocurrency Prices**: Get current prices and 24-hour changes for Bitcoin, Ethereum, and other cryptocurrencies.
- **Market Overview**: View data on top cryptocurrencies by market capitalization.
- **Crypto Knowledge**: Ask questions about blockchain, tokens, DeFi, NFTs, wallets, exchanges, and more.
- **Web Search Integration**: Utilizes DuckDuckGo search to provide up-to-date information.
- **Interactive Chat Interface**: User-friendly chat interface with message history.

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/klacrt.git
   cd klacrt
   ```

2. Install required packages:
   ```
   pip install -r requirements.txt
   ```

3. Create a `.env` file with your API keys:
   ```
   GROQ_API_KEY=your_groq_api_key
   ```

## Usage

1. Run the Streamlit application:
   ```
   streamlit run app.py
   ```

2. Open your browser and go to `http://localhost:8501`

3. Start chatting with Klacrt by asking questions about cryptocurrencies:
   - "What's the current Bitcoin price?"
   - "Show me the top cryptocurrencies by market cap"
   - "What is DeFi?"
   - "How do blockchain transactions work?"
   - "What's the price of Ethereum?"

## Dependencies

- Python 3.8+
- Streamlit
- LangChain
- Groq API (for LLM)
- Requests
- python-dotenv

## Requirements.txt

streamlit
langchain
langchain-groq
langchain-community
requests
python-dotenv

## Data Sources

- CoinGecko API for cryptocurrency market data
- DuckDuckGo search for up-to-date information
- Groq LLM (Llama 3 70B) for natural language processing

## Security Notes

- API keys should be stored in environment variables (not hardcoded)
- This app is for educational and informational purposes only
- Cryptocurrency markets are volatile - information provided is not financial advice

## License

MIT License
