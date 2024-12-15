# CreditCard-Fraud-Detection

<img align="left" width="250" height="150" src="Image/creditcard.jpeg" style="margin-right: 15px;"> **Company ABC**, a major **credit card company**, faces challenges with their existing **fraud detection system**. The current system exhibits **slow responsiveness** in recognizing new **patterns of fraud**, leading to **significant financial losses**.  

To address this issue, they have contracted us to **design** and **implement** an **algorithm** that can **efficiently identify** and **flag** potentially **fraudulent transactions** for further **investigation**. 


## Data
The [data](https://www.kaggle.com/datasets/iabhishekofficial/creditcard-fraud-detection) provided consists of two tables which are:
* ***"cc_info" :*** containing general credit card and cardholder information;
* ***"transactions" :*** containing details of credit card transactions that occurred between August 1st and October 30th.

<h3>"cc_info.csv" column Descriptions</h3>
<table border="1" style="border-collapse: collapse; width: 100%;">
<tr>
<th>Column Name</th>
<th>Description</th>
</tr>
<tr>
<td><code>credit_card</code></td>
<td>A unique identifier for each transaction.</td>
</tr>
<tr>
<td><code>city</code></td>
<td>The city where the transaction took place.</td>
</tr>
<tr>
<td><code>state</code></td>
<td>The state or region where the transaction took place.</td>
</tr>
<tr>
<td><code>zipcode</code></td>
<td>The zip code where the transaction was located.</td>
</tr>
<tr>
<td><code>credit_card_limit</code></td>
<td>Credit limit associated with the card used for the transaction.</td>
</tr>
</table>



<h3>"Transaction" column Descriptions.csv</h3>
<table border="1" style="border-collapse: collapse; width: 100%;">
<tr>
<th>Column Name</th>
<th>Description</th>
</tr>
<tr>
<td><code>credit_card</code></td>
<td>Unique identifier for each transaction.</td>
</tr>
<tr>
<td><code>date</code></td>
<td>Date of the transaction (between August 1 and October 30).</td>
</tr>
<tr>
<td><code>transaction_dollar_amount</code></td>
<td>Dollar amount of the transaction.</td>
</tr>
<tr>
<td><code>Long</code></td>
<td>Longitude coordinate of the location of the transaction.</td>
</tr>
<tr>
<td><code>Lat</code></td>
<td>Latitude coordinate of the transaction location.</td>
</tr>
<tr>
<td><code>credit_card_limit</code></td>
<td>Credit limit associated with the card used for the transaction.</td>
</tr>
</table>

## Objective
The **primary goal of this project is to build an advanced fraud detection system using neural networks to identify transactions that appear unusual and potentially fraudulent**. To be more specific, to develop a scalable solution that can handle large volumes of data and provide valuable insights to Company ABC.
