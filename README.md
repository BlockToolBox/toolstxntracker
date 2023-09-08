# toolstxntracker
toolstxntracker

Today we bring you a very simple API integration that lets you track buys and sells on a Token. 
You will need a FREE Etherscan API Key here: https://docs.etherscan.io/getting-started/viewing-api-usage-statistics


**As always we have kept it simple and meaningful for you to follow along quickly!**


First, we get the current timestamp, we will need this to retrieve the latest block txns for the token you want to track
Then we get the Block # by timestamp
Then we get all the txns for a contract address from inception till current
We now have all the data we need! From here it's a matter of choosing to display all, or 10, or 50. Displaying only buys and sells, adding a line for tax transactions, etc. 
We also give the Address field a link back to Etherscan so the user can see what happened in that transaction. 


**How**
Replace the API Key in the code below with yours 
Load the below on VS Code and open with the Live Server extension (it's free)
Change the token contract address in the 2nd API call (for the below example, Blocktools CA has been used) to the token you want to track. 
Change the "From" and "To" address from the Blocktools Uni V2 Pair address to the Pair Address of the token you want to track. 
If the tracking token of your choice has tax, you can change the "To" address from the Blocktools CA to the token address you are tracking. 

That's it, you're ready to go!


**Upgrades you can try:**

Give it styliing
Add multiple tokens 
Display transfers separately from Buy/Sells
