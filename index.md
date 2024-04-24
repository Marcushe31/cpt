---
layout: default
title: Student Blog
---
<script>
// Math Quiz Program
// Define the questions and correct answers
var questions = ["What is 2 + 2?", "What is 3 * 4?", "What is 10 - 5?"];
var answers = [4, 12, 5];
// Initialize score
var score = 0;
// Loop through each question and ask the user
for (var i = 0; i < questions.length; i++) {
    console.log("Question " + (i+1));
    console.log(questions[i]);
    var user_answer = parseInt(prompt("Your answer: "));
    
    // Check if the answer is correct
    if (user_answer === answers[i]) {
        console.log("Correct!");
        score++;
    } else {
        console.log("Incorrect!");
    }
    console.log("");
}

// Display final score
console.log("Quiz complete!");
console.log("Your score: " + score + " out of " + questions.length);
</script>