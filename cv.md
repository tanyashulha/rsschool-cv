1.	Tatsiana Shulha
2.	Contacts:
*	Telegram - @tatsianashulha
*	Phone - 375256755301
*	Skype - live:c4afb6c6ee7a6140
3. Little information about me: 
* My career aspirations are gaining excellent practical knowledge of JS, having been exposed to my current skills in a deeper way and being exposed to new skills in a meaningful way(React, Angular, Node.js), English (Intermediate).
*	My strengths are: I'm very responsible, I like to fulfil my abilities, I'm friedly and sociable person, the ability to work in a team, the desire for development, the willingness to learn new technologies, an adequate perception of criticism. Also I set goals and go to them, I'm looking for new ways of thinking.
*	In my free time I like to read, practice meditation, listen to mantra and classical music, cook delicious dishes and walk in the park.
4.	Excellent khowledge of HTML, CSS(SASS, SCSS), theoretical and some practical knowledge of JS, MySQL, MongoDB
5.  Example of my code :
function evaluateTicTacToePosition(position) { let result;
let successCombinArr = [[0, 1, 2], [3, 4, 5], [6, 7, 8], [0, 3, 6], [1, 4, 7], [2, 5, 8], [0, 4, 8], [2, 4, 6]];
(let i = 0; i < position.length; i++) { position[i].length = 3;
for(let j = 0; j < position[i].length; j++) { if(!position[i][j]) { position[i][j] = null; } } }
let currArr = position.flat();
successCombinArr.forEach((comb) => { let successArr = comb.map((i) => currArr[i]);
if(!successArr.includes('X') && !successArr.includes(null)) { result = '0'; }
if(!successArr.includes('0') && !successArr.includes(null)) { result = 'X'; }
})
return result; }

6.	Front-end Developer (work only with NTML, CSS, and JS a little) - two years
7.	Education (including courses, seminars, lectures, online learning)
8.	Now, I suppose I can say my English level is B1. Also I continue to study with a teacher three times a week.
