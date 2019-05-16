# Data_Analysis_R_Project
Impact of Buy-Online-Pick-Up-In-Store (BOPS) Strategy

<h2>Introduction</h2>

Omni-channel order fulfillment is all about giving the customer increased choices while reducing the costs of fulfillment. Implementing a BOPS strategy is another way that large retailers like Walmart, Target, JCPenny, etc., with extensive network of physical locations, have begun to use it as both a differentiator and to drive profits. Customers are also benefitting in terms of increased choices, no shipping costs, lesser wait times, convenience, fewer returns, etc. 

This project analyzes the impact of implementation of BOPS strategy for a jewelry retailer across three online channels. 

<h2>Data Overview</h2>

The data covers all online transactions made between August 1st, 2010 and July 31st, 2013 for three online channels with store numbers - 2, 6, and 5998.
<ul>
  <li>Online channels 2 and 6 started the BOPS strategy on August 1st, 2011.</li>
  <li>Online channel 5998 started the BOPS strategy on September 27th, 2012.</li>
</ul>
<p><b>Transaction Level Data</b> - This dataset included all transactions made between August 1st, 2010 and July 31st, 2013.<br>
  <b>Consumer Level Data</b> - This dataset included purchase information for all customers who both, made at least one purchase before   the BOPS implementation and made at least one purchase after the BOPS implementation. <br>
  <b>Online Daily Data</b> - This dataset was captured in two different ways:</p>
<ul>
  <li>Online daily sales-returns dataset, which included sales and returns at each online store for a given day.</li>
  <li>Online daily prod_cat sales-returns dataset, which included sales and returns for each product category at a given online store for a given day.</li>
</ul>

<h2>Research Questions</h2>

What is the impact of implementing BOPS on: 
1) Overall online channel sales and return ?
Sales: Overall online sales value and quantity indicated a decrease against an expected increase.
Returns: Overall return value and quantity indicated a decrease.

2) Online customer purchase and return behavior?
Purchase: BOPS customers made less online purchases compared to other online customers.
Returns: BOPS customers tend to return more compared to other online customers.

3) Product level sales and returns ? 
Sales: Product level online sales decreased for most of the categories.
Returns: Product level returns decreased more for certain categories compared to others.


<h2>Analysis</h2>

Analysis included use of Linear Instrumental Variables Regression, 2SLS, Count Data & Binary Outcome models, with the following key takeaways:
<ul>
<li>Convenience to check availability of a product in a physical store through the website, leads to increased physical store sales and decreased online sales.</li>
<li>Inventory information leading customers to visit their nearest store for quality assurance and ordering online to use online discounts, is resulting in reduced returns for online purchases.</li>
<li>BOPS users have easy access to the store and might prefer to do most of the purchases in-store, given that the inventory information is now available.</li>
<li>Ease of return at the store that comes with using BOPS service is a likely explanation of the higher probability of customer return behavior.</li>
</ul>
