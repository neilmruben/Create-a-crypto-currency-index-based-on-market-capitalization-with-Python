# Create-a-crypto-currency-index-based-on-market-capitalization-with-Python

### Here we want to create a crypto currency index with the 5 biggest markets capitalizations of crypto currencies. On November 2021, the 5 biggest markets capitalizations are Bitcoin, Ethereum, Binance coin, Tether and Solana.
### We grab our data from CoinMarketCap.
### Market Value-Weighted Index : ![image](https://user-images.githubusercontent.com/81652761/142762314-5c5d3fa6-62e2-465e-b9c1-b9a72f7a4a23.png)
### where p is the price of the crypto-currency and n the number of crypto-currency issued. To upscale the index, we will divide it by ![image](https://user-images.githubusercontent.com/81652761/142743336-955df7c2-218e-4730-8c3a-96b8c809d754.png). 

![image](https://user-images.githubusercontent.com/81652761/142743346-0f495860-993f-4459-b8ce-3fa01ef2d3dd.png)
MCI V daily return :
![image](https://user-images.githubusercontent.com/81652761/142743348-667ed220-5d23-4bf0-b94f-1e1436606150.png)
### By creating a crypto index we can now assess the general performance of the crypto-currencies markets. We will use it to apply the Capital Asset Pricing Model (CAPM)  introduced by Jack Treynor (1961, 1962), William F. Sharpe (1964), John Lintner (1965) and Jan Mossin (1966), building on the earlier work of Harry Markowitz on diversification and modern portfolio theory.
# CAPM :
### ![image](https://user-images.githubusercontent.com/81652761/142743380-814d0a19-577f-41fe-a6fe-d3e0a4cc68bd.png)
### Where E(Rm) will be the expected return of the crypto market embodie by MCI 5 and ![image](https://user-images.githubusercontent.com/81652761/142743393-d33bc7d7-abe5-4bff-8e2a-72069a6b8a43.png) is the sensitivity of the expected excess asset returns to the expected excess market returns and ![image](https://user-images.githubusercontent.com/81652761/142743398-0d4ac3b3-b0fd-4168-bb07-94f23e31c229.png)
