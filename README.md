# custom-JavaScript-calculator
this is my calculator I made with JavaScript 
Basic Operations & Square Root Recipe
let n = Number(prompt("type in your first number")); let opt = prompt("type in your operator"); let s = Number(prompt("type in your second number"));  if (opt === "+") {     console.log(n + s); } else if (opt === "-") {     console.log(n - s); } else if (opt === "/") {     console.log(n / s); } else if (opt === "*") {     console.log(n * s); } else if (opt === "sqrt") {     console.log(Math.sqrt(n)); // Only needs 'n' } else {     console.log("by omar adel"); } 
Key Takeaways
	•	Curly Braces {}: Used as code blocks to group statements together.
	•	Else If Chain: Ensures only one matching block runs and the final else catches invalid operators.
	•	Math Object: Built-in JavaScript tool like Math.sqrt() used for advanced math functions.
