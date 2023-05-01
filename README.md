Download Link: https://assignmentchef.com/product/solved-cind110-assignment3-association-rules
<br>
<ol>

 <li>Association rules:</li>

</ol>

One of the major techniques in data mining involves the discovery of association rules. These rules correlate the presence of a set of items with another range of values for another set of variables. The database in this context is regarded as a collection of transactions, each involving a set of items, as shown below.

Trans ID      Items Purchased

<ul>

 <li>Meat, Potato, Onion</li>

 <li>Meat, Noodle</li>

 <li>Noodle, Spinach</li>

 <li>Meat, Potato, Onion</li>

 <li>Onion, Potato, Noodle</li>

 <li>Eggs, Spinach</li>

 <li>Eggs, Noodle</li>

 <li>Meat, Potato, Salt, Onion</li>

 <li>Salt, Spinach</li>

 <li>Meat, Potato</li>

 <li>Apply the Apriori algorithm on this dataset.</li>

</ul>

Note that, the set of items is {Meat, Potato, Onion, Noodle, Spinach, Eggs, Salt}.  You may use 0.3 for the minimum support value.

<ul>

 <li>Show the rules that have a confidence of 0.8 or greater for an itemset containing three items.</li>

</ul>

<ol start="2">

 <li>Classification:</li>

</ol>

Classification is the process of learning a model that describes different classes of data and

the classes should be pre-determined. Consider the following set of data records:

<table width="530">

 <tbody>

  <tr>

   <td width="80">ID</td>

   <td width="69">Age</td>

   <td width="53">City</td>

   <td width="62">Gender</td>

   <td width="135">Education</td>

   <td width="131">Profile</td>

  </tr>

  <tr>

   <td width="80"> 101</td>

   <td width="69"> 20-30</td>

   <td width="53"> NY</td>

   <td width="62">F</td>

   <td width="135"> College</td>

   <td width="131"> Employed</td>

  </tr>

  <tr>

   <td width="80">102</td>

   <td width="69">31-40</td>

   <td width="53">NY</td>

   <td width="62">F</td>

   <td width="135">College</td>

   <td width="131">Employed</td>

  </tr>

  <tr>

   <td width="80">103</td>

   <td width="69">51-60</td>

   <td width="53">NY</td>

   <td width="62">F</td>

   <td width="135">College</td>

   <td width="131">Unemployed</td>

  </tr>

  <tr>

   <td width="80">104</td>

   <td width="69">20-30</td>

   <td width="53">LA</td>

   <td width="62">M</td>

   <td width="135">High School</td>

   <td width="131">Unemployed</td>

  </tr>

  <tr>

   <td width="80">105</td>

   <td width="69">41-50</td>

   <td width="53">NY</td>

   <td width="62">F</td>

   <td width="135">College</td>

   <td width="131">Employed</td>

  </tr>

  <tr>

   <td width="80">106</td>

   <td width="69">41-50</td>

   <td width="53">NY</td>

   <td width="62">F</td>

   <td width="135">Graduate</td>

   <td width="131">Employed</td>

  </tr>

  <tr>

   <td width="80">107</td>

   <td width="69">20-30</td>

   <td width="53">LA</td>

   <td width="62">M</td>

   <td width="135">College</td>

   <td width="131">Employed</td>

  </tr>

  <tr>

   <td width="80">108</td>

   <td width="69">20-30</td>

   <td width="53">NY</td>

   <td width="62">F</td>

   <td width="135">High School</td>

   <td width="131">Unemployed</td>

  </tr>

  <tr>

   <td width="80">109</td>

   <td width="69">20-30</td>

   <td width="53">NY</td>

   <td width="62">F</td>

   <td width="135">College</td>

   <td width="131">Employed</td>

  </tr>

  <tr>

   <td colspan="6" width="530">       110         51-60          SF             M        College                       Unemployed </td>

  </tr>

 </tbody>

</table>




Assuming, that the class attribute is Profile, apply a classification algorithm to this dataset.

<ol start="3">

 <li>Clustering: Consider the following set of two-dimensional records:</li>

</ol>




RID                  Age                    Years of Service

<ul>

 <li>30 5</li>

 <li>50 25</li>

 <li>50 15</li>

 <li>25 5</li>

 <li>30 10</li>

 <li>55 25</li>

</ul>




<ul>

 <li>Marks:</li>

</ul>

Use the K-means algorithm to cluster this dataset. You can use a value of 2 for K and can assume that the records with RIDs 103, and 104 are used for the initial cluster centroids.

<ul>

 <li>Marks:</li>

</ul>

What is the difference between describing discovered knowledge using clustering and describing it using classification?