Download Link: https://assignmentchef.com/product/solved-datamining-homework3
<br>
<ul>

 <li>Consider the Utility Matrix Below that represents the ratings, on a 1-5 scale, of eight items, a through h, by three users: A, B, and C. Compute the following from the data of this matrix.</li>

</ul>

<sub>                                                          </sub>items

<table width="447">

 <tbody>

  <tr>

   <td width="23"></td>

   <td width="424">


    <table width="420">

     <tbody>

      <tr>

       <td width="50"> </td>

       <td width="31">A</td>

       <td width="15"> </td>

       <td width="32">b</td>

       <td width="15"> </td>

       <td width="31">c</td>

       <td width="15"> </td>

       <td width="32">d</td>

       <td width="15"> </td>

       <td width="31">e</td>

       <td width="15"> </td>

       <td width="30">f</td>

       <td width="15"> </td>

       <td width="31">g</td>

       <td width="15"> </td>

       <td width="32">h</td>

       <td width="15"> </td>

      </tr>

      <tr>

       <td width="50">A</td>

       <td width="31"> </td>

       <td width="15">5</td>

       <td width="32"> </td>

       <td width="15">4</td>

       <td width="31"> </td>

       <td width="15"> </td>

       <td width="32"> </td>

       <td width="15">5</td>

       <td width="31"> </td>

       <td width="15">2</td>

       <td width="30"> </td>

       <td width="15"> </td>

       <td width="31"> </td>

       <td width="15">3</td>

       <td width="32"> </td>

       <td width="15">2</td>

      </tr>

      <tr>

       <td width="50">B</td>

       <td width="31"> </td>

       <td width="15"> </td>

       <td width="32"> </td>

       <td width="15">3</td>

       <td width="31"> </td>

       <td width="15">4</td>

       <td width="32"> </td>

       <td width="15">4</td>

       <td width="31"> </td>

       <td width="15">2</td>

       <td width="30"> </td>

       <td width="15">2</td>

       <td width="31"> </td>

       <td width="15">1</td>

       <td width="32"> </td>

       <td width="15"> </td>

      </tr>

      <tr>

       <td width="50">C</td>

       <td width="31"> </td>

       <td width="15">3</td>

       <td width="32"> </td>

       <td width="15"> </td>

       <td width="31"> </td>

       <td width="15">1</td>

       <td width="32"> </td>

       <td width="15">4</td>

       <td width="31"> </td>

       <td width="15"> </td>

       <td width="30"> </td>

       <td width="15">4</td>

       <td width="31"> </td>

       <td width="15">5</td>

       <td width="32"> </td>

       <td width="15">3</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>










<ol>

 <li>Treating the utility matrix as Boolean, compute the Jaccard distance between each pair of users.</li>

 <li>Repeat Part A, but use the cosine distance.</li>

 <li>Treat ratings of 3, 4, and 5 as 1, and ratings 1, 2, and blank as zero. Compute the Jaccard distance between each pair of users.</li>

 <li>Repeat Part C, but use the cosine distance.</li>

 <li>Normalize the matrix by subtracting from each nonblank entry the average value for its user.</li>

 <li>Using the normalized matrix from Part E, compute the cosine distance between each pair of users.</li>

</ol>







<ul>

 <li>ISLR Chapter 10 Question 2</li>

</ul>







<ul>

 <li>Adapted from ISLR Chapter 10 Question 10.

  <ol>

   <li>Generate a simulated data set with 20 observations in each of three classes (i.e. 60 observations total) and 50 variables.</li>

  </ol></li>

</ul>

Hint: there are a number of functions in R that you can use to generate data, rnorm() and runif() are two options.  Be sure to add a mean shift to the observations in each class so that there are three distinct classes – remember to set.seed().




<ol start="3">

 <li>Perform k-means clustering of the observations with K=3. Using the rand index and adjusted rand index, assess how well do the clusters that you obtained in K-means clustering compare to the true labels?</li>

</ol>




<ol>

 <li>Using silhouette plots, select the optimal number of clusters.</li>

</ol>




<ol>

 <li>Using the gap statistics, select the optimal number of clusters.</li>

</ol>





