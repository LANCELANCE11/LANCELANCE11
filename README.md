- 👋 Hi, I’m @LANCELANCE11
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
LANCELANCE11/LANCELANCE11 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
/* 
  1. Store correct answers
   - When quiz begins, no answers are correct
    
*/
 
// 2. Store the rank of a player


// 3. Select the <main> HTML element

const main = document.querySelector('main');
const string1 = "Whats Is Number?";
const string2 = "Whats Is Name?";
const string3 = "Whats Is Favorite?";

/*
  4. Ask at least 5 questions
   - Store each answer in a variable
   - Keep track of the number of correct answers
*/


/*
  5. Rank player based on number of correct answers
   - 5 correct = Gold
   - 3-4 correct = Silver
   - 1-2 correct = Bronze
   - 0 correct = No crown
*/
 


// 6. Output results to the <main> element

main.innerHTML = `
    <h2>You got ${correct} out of 5 questions correct.</h2>
    <p>Crown earned: <strong>${rank}</strong></p>`;
