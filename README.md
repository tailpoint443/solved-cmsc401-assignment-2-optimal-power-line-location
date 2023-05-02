Download Link: https://assignmentchef.com/product/solved-cmsc401-assignment-2-optimal-power-line-location
<br>
<h1>Optimal Power Line Location</h1>

<ul>

 <li>Power distribution company is planning to build a main power line from east to west (x-axis) across its distribution area</li>

 <li></li>

</ul>

<table>

 <tbody>

  <tr>

   <td width="782"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>The area has n houses</li>

 <li>The company wants to connect each house directly to the main power line with smaller power lines in north-south direction (y-axis)</li>

</ul>

<table width="750">

 <tbody>

  <tr>

   <td colspan="3" width="308"></td>

   <td width="161"></td>

   <td colspan="2" width="281"></td>

  </tr>

  <tr>

   <td width="116"></td>

   <td width="130"></td>

   <td colspan="3" width="403"></td>

   <td width="102"></td>

  </tr>

  <tr>

   <td width="116"></td>

   <td width="133"></td>

   <td width="70"></td>

   <td width="188"></td>

   <td width="168"></td>

   <td width="74"></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Your task is to estimate the optimal position (on the y-axis) of the main power line, so that the total length of smaller power lines is the shortest.</li>

</ul>

<h1>Assignment 2</h1>

Write a program cmsc401.java that

<ul>

 <li>takes as input

  <ul>

   <li>in the first line, the number of houses n, n&gt;=2, n&lt;1,000,000</li>

   <li>in each consecutive line (from 2<sup>nd </sup>to (n+1)-th line), the ycoordinate of one house (integers in the range 0 to</li>

  </ul></li>

</ul>

1,000,000,000)

<ul>

 <li>returns as output

  <ul>

   <li>a single number: the y-coordinate where the main power line should be built</li>

   <li>only one number, no comments, prompts etc.</li>

  </ul></li>

 <li>Use standard I/O to read input (System.in, System.out) and write the result</li>

 <li>Make sure the program compiles</li>

</ul>

<h1>Example</h1>

<table width="39">

 <tbody>

  <tr>

   <td width="39">5</td>

  </tr>

 </tbody>

</table>

Input            Output

Total length of smaller power lines: 15 This is the minimum possible length.

There might be other results with the same minimum

<h1>Hints</h1>

<ul>

 <li>Think about the solution over examples</li>

 <li>Consider the y-coordinates of houses as an array of size n</li>

 <li>Design a divide &amp; conquer algorithm like quicksort

  <ul>

   <li>Use recursive approach with an appropriate <em>Partitionlike </em>method</li>

  </ul></li>

 <li>Try to use the asymptotically fastest method

  <ul>

   <li>Aim at expected linear time O(n)</li>

   <li>Slower methods will get lower score even it is correct</li>

  </ul></li>

 <li>There may be several correct solutions, return one of them.</li>

</ul>