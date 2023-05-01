Download Link: https://assignmentchef.com/product/solved-c-programming-language-project-9
<br>
In this project, you must create a music stack list which has The Turkish Five. The Turkish Five is a name used to identify five pioneers of western classical music in Turkey. The Turkish Five composers are listed below in the table.




<table width="503">

 <tbody>

  <tr>

   <td width="107"><strong>Name (char []) </strong> </td>

   <td width="124"><strong>Surname (char [] </strong> </td>

   <td width="175"><strong>Musical_Work(char []) </strong> </td>

   <td width="97"><strong>age (int) </strong> </td>

  </tr>

  <tr>

   <td width="107">Cemal Reşit </td>

   <td width="124">Rey </td>

   <td width="175">Lüküs Hayat </td>

   <td width="97">80 </td>

  </tr>

  <tr>

   <td width="107">Ahmed Adnan </td>

   <td width="124">Saygun </td>

   <td width="175">Yunus Emre </td>

   <td width="97">83 </td>

  </tr>

  <tr>

   <td width="107">Ulvi Cemal </td>

   <td width="124">Erkin </td>

   <td width="175">Keloğlan </td>

   <td width="97">66 </td>

  </tr>

  <tr>

   <td width="107">Hasan Ferit </td>

   <td width="124">Alnar </td>

   <td width="175">Sarı Zeybek </td>

   <td width="97">72 </td>

  </tr>

  <tr>

   <td width="107">Necil Kazım </td>

   <td width="124">Akses </td>

   <td width="175">İkinci Senfoni </td>

   <td width="97">90 </td>

  </tr>

 </tbody>

</table>




Create a stack that is implemented with a linked list. You must define <strong>struct person</strong> like;




<strong>struct person{ </strong>




<strong>name (char[]); </strong>




<strong>surname (char[]); </strong>




<strong>musical_Work(char[]); </strong>




<strong>age(int); </strong>




<strong>struct person *next; </strong>




<strong>} *top; </strong>




In your program, you have to create a menu which has the following operations.




<ul>

 <li>Add a Person to the Stack</li>

</ul>




Take person’s information with scanf, create a node and add the node to the stack using the

function <strong>addNode(char name[], char surname [], char creation [], int age). </strong>




Page <strong>1</strong> of <strong>5 </strong>

<ul>

 <li>Pop a Person from the Stack</li>

</ul>




Delete the last node of the stack. Create <strong>deleteNode(…)</strong> to pop a node.




<ul>

 <li>Sort in Alphabetical Order</li>

</ul>




<sub> </sub>Write a method <strong>Sort_Alphabetically(…)</strong> to order the names of the people in the stack alphabetically. Use the <strong>print_stack(…)</strong> method to show the sorted stack.




<ul>

 <li>Sort Age in Increasing Order</li>

</ul>




Write a method <strong>Sort_Increasingly(…)</strong> that sorts ages of people in the stack in increasing order. Use the <strong>print_stack(…)</strong> method to show the sorted stack<strong>. </strong>




<ul>

 <li>Exit menu</li>

</ul>




Quit menu.







<strong>Example Output; (User entered values are written in bold.) </strong>




****MENU****

<ul>

 <li>Add a Person to the Stack</li>

 <li>Pop a Person from the Stack</li>

 <li>Sort Alphabetical Order</li>

 <li>Sort Age in Increasing Order</li>

 <li>Exit menu</li>

</ul>

*************

Select your Choise: <strong>1 </strong>

Name: <strong>Cemal Reşit </strong>Surname: <strong>Rey </strong>

Creation: <strong>Lukus Hayat </strong>

Age: <strong>80 </strong>

——————–

1)Cemal Reşit

Rey

Lukus Hayat

80

****MENU****

<ul>

 <li>Add a Person to the Stack</li>

 <li>Pop a Person from the Stack</li>

 <li>Sort in Alphabetical Order</li>

 <li>Sort Age in Increasing Order</li>

 <li>Exit menu</li>

</ul>

*************

Select your Choise: <strong>1 </strong>

Name: <strong>Ahmed Adnan </strong>

Surname: <strong>Saygun </strong>

Creation: <strong>Yunus Emre </strong>

Age: <strong>83 </strong>

——————–

1) Ahmed

Adnan Saygun

Yunus Emre

83

2)Cemal Reşit

Rey

Lukus Hayat

80

****MENU****

<ul>

 <li>Add a Person to the Stack</li>

 <li>Pop a Person from the Stack</li>

 <li>Sort in Alphabetical Order</li>

 <li>Sort Age in Increasing Order</li>

 <li>Exit menu</li>

</ul>

Select your Choise: <strong>1 </strong>

*************

Name: <strong>Ulvi Cemal </strong>

Surname: <strong>Erkin </strong>

Creation: <strong>Keloğlan </strong>

Age: <strong>66 </strong>

—————–

<ul>

 <li>Ulvi Cemal Erkin</li>

</ul>

<sub> </sub>Keloğlan

66

<ul>

 <li>Ahmed</li>

</ul>

Adnan Saygun

Yunus

Emre 83

3)Cemal Reşit

Rey

Lukus

<sub> </sub>Hayat 80

<sub> </sub>****MENU****

<ul>

 <li>Add a Person to the Stack</li>

 <li>Pop a Person from the Stack 3- Sort in Alphabetical Order</li>

 <li>Sort Age in Increasing Order</li>

 <li>Exit menu</li>

</ul>




*************

Select your Choise: <strong>1 </strong>

Name: <strong>Hasan Ferit </strong>

Surname: <strong>Alnar </strong>

Creation: <strong>Sarı Zeybek </strong>Age: <strong>72 </strong>

——

<ul>

 <li>Hasan</li>

</ul>

<sub> </sub>Ferit Alnar Sarı Zeybek

72

<ul>

 <li>Ulvi Cemal Erkin</li>

</ul>

<sub> </sub>Keloğlan

66

<ul>

 <li>Ahmed</li>

</ul>

Adnan Saygun

Yunus

Emre 83

4)Cemal Reşit

Rey

Lukus Hayat

80

****MENU****

<ul>

 <li>Add a Person to the Stack</li>

 <li>Pop a Person from the Stack</li>

 <li>Sort in Alphabetical Order</li>

 <li>Sort Age in Increasing Order</li>

 <li>Exit menu</li>

</ul>




*************




Select your Choise: <strong>2 </strong>

<ul>

 <li>Ulvi Cemal Erkin</li>

</ul>

<sub> </sub>Keloğlan

66

<ul>

 <li>Ahmed</li>

</ul>

Adnan Saygun

Yunus

Emre 83

3)Cemal Reşit

Rey

Lukus

<sub> </sub>Hayat 80

<sub> </sub>****MENU****

<ul>

 <li>Add a Person to the Stack</li>

 <li>Pop a Person from the Stack 3- Sort in Alphabetical Order</li>

 <li>Sort Age in Increasing Order</li>

 <li>Exit menu</li>

</ul>




*************

Select your Choise: <strong>3 </strong>

Ahmed Adnan

Saygun

Yunus Emre 83

Cemal Reşit

Rey

Lukus Hayat

80

Ulvi Cemal

Erkin Keloğlan

66

****MENU****

<ul>

 <li>Add a Person to the Stack</li>

 <li>Pop a Person from the Stack</li>

 <li>Sort in Alphabetical Order</li>

 <li>Sort Age in Increasing Order</li>

 <li>Exit menu</li>

</ul>




*************

Select your Choise: <strong>4 </strong>

Ulvi Cemal

Erkin

Keloğlan

66




Cemal Reşit

Rey

Lukus Hayat

80

Ahmed Adnan

Saygun

Yunus Emre

83










Page <strong>5</strong> of <strong>5 </strong>