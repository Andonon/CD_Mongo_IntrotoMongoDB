# CD_Mongo_IntrotoMongoDB
Troy Center troycenter1@gmail.com July 2017
Coding Dojo MEAN stack, Intro to Mongo assignment. 

<h3>Assignment: Intro to MongoDB</h3>
For This section, we want you to do the following operations in a MongoDB database. Work with a partner or a small group so everyone gets a chance to collaborate and work as a team. For some of these, you may have to refer to MongoDB's operator documentation. This is one of the most important assignments in this section, make sure you answer all questions and take notes for future assignments.

<a href="http://docs.mongodb.org/manual/reference/operator/"></a>

<ol>
<li>Create a database called 'my_first_db'.</li>
<li>Create students collection.</li>
<li>Each document you insert into this collection should have the following format: ({name: STRING, home_state: STRING, lucky_number: NUMBER, birthday: {month: NUMBER, day: NUMBER, year: NUMBER}})</li>
<li>Create 5 students with the appropriate info.</li>
<li>Get all students.</li>
<li>Retrieve all students who are from California (San Jose Dojo) or Washington (Seattle Dojo).</li>
<li>Get all students whose lucky number is:</li>
<ol>
<li>greater than 3</li>
<li>less than or equal to 10</li>
<li>between 1 and 9 (inclusive)</li>
</ol>
<li>Add a field to each student collection called 'interests' that is an ARRAY.  It should contain the following entries: 'coding', 'brunch', 'MongoDB'. Do this in ONE operation.</li>
<li>Add some unique interests for each particular students into each of their interest arrays.</li>
<li>Add the interest 'taxes' into someone's interest array.</li>
<li>Remove the 'taxes' interest you just added.</li>
<li>Remove all students who are from California (or Washington).</li>
<li>Remove a user by name. </li>
<li>Remove a student whose lucky number is greater than 5 (JUST ONE)</li>
<li>Add a field to each student collection called 'number_of_belts' and set it to 0.</li>
<li>Increment this field by 1 for all students in Washington (Seattle Dojo).</li>
<li>Rename the 'number_of_belts' field to 'belts_earned'</li>
<li>Remove the 'lucky_number' field.</li>
<li>Add a 'updated_on' field, and set the value as the current date.</li>
</ol>