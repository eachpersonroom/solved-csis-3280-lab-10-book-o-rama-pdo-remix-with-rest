Download Link: https://assignmentchef.com/product/solved-csis-3280-lab-10-book-o-rama-pdo-remix-with-rest
<br>
Visual Studio Code

<ol>

 <li>Download the lab template from Blackboard</li>

 <li>Extract it</li>

 <li>Fill in the relevant code to create the solution and meet the requirements</li>

</ol>

Solution

Based on the Demo Code and the bookorama database. Create a Web application that allows you to add and delete Customers using a web service.

You may use the demo code from Week 12 as reference to this part of the Lab, create the application so the following list of customers is presented and the Delete link works for each Customer. The add form should always be present unless you are editing, in which case the edit form should always be present, and the message should come up as to which customer was added.

<h1>Requirements</h1>

<ol>

 <li>You must use a database called “Lab10″, your username should be ‘root’ and your password should be ” just like the lab computers.</li>

 <li></li>

</ol>

<table>

 <tbody>

  <tr>

   <td width="57"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<ul>

 <li><strong>You must populate the ‘Lab10’ database with the included sql files (sql/bookorama.sql and sql/books-insert.sql)</strong></li>

</ul>

<ol start="3">

 <li>You must use the PDO class we created based on the template provided.</li>

 <li>You must use classes you should not alter the PDO class we have created.</li>

 <li>You must list all the customers in the database and provide the provisions to add and delete Customers</li>

 <li>By default the Add form should be displayed, if the user clicks on the “Edit” action or link you must allow them to edit the entry they clicked on.</li>

 <li>You may only use one controller file.</li>

 <li>Your controller file may only call your RestClient. You may not talk directly to the database from your page controller or from your RestClient.</li>

 <li><strong>You must configure your lab so the included location of the REST API</strong></li>

</ol>

<strong>(http://localhost/3280/Lab%2010/RestAPI.php) is valid. You may not modify API_URL in config.inc.php.</strong>

<ol start="10">

 <li>You must employ a static “Mapper” class to support your CRUD operations. Your Mapper class must use the Customer Class. You may not use any array elements that are not objects.</li>

 <li>As you are using a previous template you must pull out any code that is not used such as the BookMapper and the Book class.</li>

</ol>

<h1>Structure</h1>

According to the structure this means that your folder should be called “Lab 10”.

<strong>FileName                                                     Description</strong>

<strong>FileName                                                     Description</strong>

<table width="0">

 <tbody>

  <tr>

   <td width="273">inc/config.inc.php</td>

   <td width="407">Database configuration information</td>

  </tr>

  <tr>

   <td width="273">inc/Utilities/PDOAgent.class.php</td>

   <td width="407">PDO Wrapper Class</td>

  </tr>

  <tr>

   <td width="273">inc/Utilities/Page.class.php</td>

   <td width="407">Page Class</td>

  </tr>

  <tr>

   <td width="273">inc/Utilities/CustomerMapper.class.php</td>

   <td width="407">Static Customer Mapper responsible for CRUD operations</td>

  </tr>

  <tr>

   <td width="273"><strong>inc/Utilities/RestClient.class.php</strong></td>

   <td width="407">Static class that calls the web service</td>

  </tr>

  <tr>

   <td width="273">inc/Entities/Customer.class.php</td>

   <td width="407">Customer Entity with getters and setters.</td>

  </tr>

  <tr>

   <td width="273">Lab10_SWh-56789.php</td>

   <td width="407">The controller class for your application, should be used to support All the CRUD operations</td>

  </tr>

 </tbody>

</table>

The Rest API that receive and respond to HTTP calls and talk to

<strong>RestAPI.php </strong>the database

Hints:

Use the hidden input type to post hidden data such as the id.

Use the hidden input type to specify which action you are doing.

There are alot of moving parts in this assignment <strong>USE XDEBUG</strong> it will save you time!

If you do the lab properly you should really only need to modify the Controller file for the page and the class for the Customer, the rest should work without any modification.

Appendix:

Included below are the screenshots from Lab08 because the Lab should be functionally the same <strong>Please change the title</strong>

<ol>

 <li>List</li>

</ol>