<h1>Develop an Algorithm</h1>



<h2>Description</h2>
<p> An algorithm is a set of steps that can be used to solve a problem. Security analysts develop algorithms to provide the solutions that they need for their work. For example, an analyst may work with users who bring them devices. The analyst may need an algorithm that first checks if a user is approved to access the system and then checks if the device that they have brought is the one assigned to them.</p>


<br />


<h2>Objective</h2>

- <b> Develop an algorithm in Python that automates this process. </b> 
- <b> You'll write code that indicates if a user is approved on the system and has brought their assigned device to the security team.</b>

<h2> Understanding Lists and Indices </h2>
<p> Explore how lists and indices work.
Use a code cell to see how elements in two lists are synchronized through indices.</p>
<img src="https://i.imgur.com/q7RCpjY.png" height="80%" width="80%" />



<h2>Program walk-through:</h2>

<p align="center">
<p>Add a New User

Given a new user's username and device ID, use the .append() method to add them to the respective approved users and devices lists.
Display the updated lists.</p> <br/>
<img src="https://i.imgur.com/5SkmUjk.png" height="80%" width="80%" />
<br />
<br />


<p> Remove a User

Given a username and device ID of an employee who has left, use the .remove() method to delete them from the lists.
Display the updated lists. </p>  <br/>
<img src="https://i.imgur.com/UN12yBR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<p>Verify User Access

Write a conditional statement to check if a given username is in the approved users list.
Display whether the user is approved or not.</p> <br/>
<img src="https://i.imgur.com/Popp54H.png" height="80%" width="80%"/>
<br />
<br />
<p>Find Index of a User

Use the .index() method to find the index of a username in the approved users list.
Display the index value.</p>  <br/>
<img src="https://i.imgur.com/FqSlBjB.png" height="80%" width="80%"/>
<br />
<br />
<p>Retrieve Device ID

Find the index of a username in the approved users list.
Use this index to retrieve the corresponding device ID from the approved devices list.
Display the device ID.</p>  <br/>
<img src="https://i.imgur.com/ESk6lW4.png" height="80%" width="80%"/>
<br />
<br />
<p>Check User-Device Correspondence

Write a conditional to verify if the username is in the approved devices list.
Check if the device ID at the same index as the username matches the provided device ID.
Display approval messages accordingly.</p>  <br/>
<img src="https://i.imgur.com/DJLMOx5.png" height="80%" width="80%"/>
<br />
<br />
<p>Handle Incorrect User-Device Pair

Add an elif statement to handle cases where the username is in approved users but the device ID doesn't match.
Display messages for an incorrect device ID.</p>  <br/>
<img src="https://i.imgur.com/8shmv5w.png" height="80%" width="80%"/>
</p>
<p>Automate the Login Process

Create a function named login that takes username and device ID as parameters.
Implement nested conditionals to automate the login process:
Check if the user is approved, and if so, check the device ID.
Test the function with different username and device ID combinations.
These steps provide a clear and organized plan for developing the user access verification algorithm.</p>  <br/>
<img src="https://i.imgur.com/waKpdo1.png" height="80%" width="80%"/>
<br />
<br />

<img src="https://i.imgur.com/I4qdwSx.png" height="80%" width="80%"/>
<br />
<br />
<h2>Review</h2>
<b>Python:</b> The primary programming language used for writing the code to manage user-device relationships and implement the security algorithm.

<b>Lists:</b> Lists are a fundamental data structure in Python used to store collections of items. In this project, they are employed to keep track of approved usernames and their corresponding devices.

<b>Conditional Statements:</b> These are used to create decision-making logic, like checking if a user is approved or whether a username matches with a device ID.

<b>Functions:</b> A key concept in Python, functions are used to encapsulate code and automate the login process, making the algorithm reusable and organized.

<b>Overall, this project leverages Python's simplicity and versatility along with basic data structures and control structures to create an efficient security algorithm.</b>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
