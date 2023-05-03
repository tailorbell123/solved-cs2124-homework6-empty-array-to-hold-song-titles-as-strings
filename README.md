Download Link: https://assignmentchef.com/product/solved-cs2124-homework6-empty-array-to-hold-song-titles-as-strings
<br>
1) You have a friend who loves singing karaoke with a big group of people. The karaoke singers add songs they’d like to sing to a list and the karaoke host calls out the songs one by one.  Your friend and has asked you to write software to help manage the song list.

<ul>

 <li>Create an empty array to hold song titles as strings, and use the append method to add three or four songs one at a time.</li>

 <li>One enthusiastic singer wants to add three songs at once. Create an array holding this one singer’s song list and use the += operator to append their whole list to the end of the group’s song list.</li>

 <li>Write a for…in loop and, for every song title in the array, print an encouraging announcement to let the next singer know that it’s their turn.</li>

 <li>After the loop has called everyone up to sing, use the removeAll method on the song list to clear out all the past songs.</li>

</ul>

2) Think of a goal of yours that can be measured in progress every day, whether it’s minutes spent exercising, number of photos sent to friends, hours spent sleeping, or number words written for your novel.

<ul>

 <li>Make a class that will track your activity!</li>

 <li>Give it a description or name</li>

 <li>Give it a goal</li>

 <li>Give it an array to keep track of daily entries. Hint: Make sure to choose the right kind of array for your data, whether [Double] or [Int].</li>

 <li>Write a function that adds a new data point to the array.</li>

 <li>Write a function that takes the daily number as an argument and returns true if the goal was met, or false if it was not.</li>

 <li>Write a function that takes the daily number as an argument and returns a message as a string. It should return a different message based on how close the number comes to your goal. You can be as ambitious and creative as you’d like with your responses, but make sure to return at least two different messages depending on your daily progress!</li>

 <li>Write a function that takes two numbers (Ints or Doubles depending on your data) and adds them together.</li>

 <li>Write a function that will print out a summary of your activity. This function should:</li>

 <li>Use filter to decide how many times you met or passed your goal this week.</li>

 <li>Use a map to generate an Array of messages based on your activity data.</li>

 <li>Join these messages together into one long string, with each message ending with “
” (new line character) Hint: Reduce or .joined(seperator: String) should work</li>

 <li>Use reduce to calculate the sum of your activity data.</li>

 <li>Use the sum and .count to calculate the average of the data.</li>

</ul>

Create an instance of your class and populate it with at least 7 data points.  Feel free to make up or embellish the numbers, but make sure you have entries that are above, below and exactly at the goal you’ve thought of. Finally, print the summary of your activity.

Here is my example of how to use this class!

<ul>

 <li>Write a function that will return the largest number stored in an array of integers. (This should sound super familiar!). Don’t use max().</li>

</ul>

BONUS:  Do it two different ways.  Once as a for…in loop, and once with map/filter/ reduce.  Which solution do you like better and why? <strong>func findMax(numbers : [Int]) -&gt; Int </strong>

<ul>

 <li>What does the following print? Don’t type this up. Just follow along with paper.</li>

</ul>


