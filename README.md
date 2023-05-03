Download Link: https://assignmentchef.com/product/solved-cpts479-assignment-10
<br>
available on Blackboard Learn. You may use my solution or your own as a starting point. See screen shots below. Specifically,

<ol>

 <li>Initialize the quiz based on five questions retrieved from the Open Trivia Database using the HTTP request “<u>https://opentdb.com/api.php?amount=5</u>”. When the app starts, it should retrieve five questions and parse the resulting JSON response to extract the questions, correct answer, and incorrect answers. The app should then display the first question.</li>

 <li>The “Next” button should be moved over to the bottom-right of the view, but otherwise function as it did in Homework 2, i.e., advance to the next question, or to the first question if on the last question. The question number at the top should be updated accordingly.</li>

 <li>Add a “New Quiz” button to the bottom-left of the view. When this is tapped, your app should retrieve a new set of five questions, replacing the previous set, and reset the view to display the first question of the new set.</li>

 <li>The correct answer for each question should not be the same, i.e., always first, always second, always last, etc. The app should randomly shuffle the answers. This can be done when the questions are first created, or each time they are displayed.</li>

 <li>The question and answer strings returned by the API use an HTML encoding by default. Unfortunately, Swift does not have a built-in HTML decoder, so you need to search for and replace HTML codes in the question and answer strings. In particular, you should replace “&amp;#039;” with a single quote and “&amp;quot;” with a double quote. There are other HTML codes that will show up, and you are encouraged to search and place those too, as appropriate. But only the single and double quote replacement is required.</li>

 <li>As usual, make sure the auto layout constraints are set so that the view elements are appropriately displayed with no overlap regardless of device orientation.</li>

</ol>







1 StoryBoard:




Simulator: