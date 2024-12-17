# **Cryptocurrency Trading System Using Deribit API**

## **Overview**  
This project demonstrates a cryptocurrency trading system built using the Deribit API. The system is designed to automate trading tasks such as placing and modifying orders, retrieving market data, and managing positions. It emphasizes modularity, efficiency, and security, making it easy to maintain and expand.

---

## **Features**  
1. **Access Token Retrieval**  
   - Authenticates with the Deribit API to obtain an access token.  
   - Ensures secure communication for further API interactions.

2. **Order Management**  
   - Place buy and sell orders for supported instruments.  
   - Modify existing orders by changing price or quantity.  
   - Cancel orders by providing the order ID.

3. **Market Data Retrieval**  
   - Fetch real-time market data, including bid and ask prices, using the order book.  
   - Useful for making informed trading decisions.

4. **Position Management**  
   - View current open positions, including size, entry price, and unrealized profit or loss.

5. **Error Handling**  
   - Logs errors for invalid responses or failed API calls, ensuring smooth execution.

---

## **Installation**  
Follow these steps to set up the project on your local system:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
