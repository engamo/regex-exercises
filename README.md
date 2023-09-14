Exercise 1 
Regexp Golf

Regular expressions for each of the given patterns:

1. `car and cat`:
   Regular Expression: `ca[rt]`
   
2. `pop and prop`:
   Regular Expression: `p[op]`

3. `ferret, ferry, and ferrari`:
   Regular Expression: `ferr(et|y|ari)`

4. `Any word ending in ious`:
   Regular Expression: `\b\w*ious\b`

5. `A whitespace character followed by a period, comma, colon, or semicolon`:
   Regular Expression: `\s[.,:;]`

6. `A word longer than six letters`:
   Regular Expression: `\b\w{7,}\b`

7. `A word without the letter e (or E)`:
   Regular Expression: `\b[^eE]+\b`

Exercise 2
Quoting Style
let message = "Hi, 'What do you do for a living?,' hmmm, 'I am a developer!'";

// Replacing single quotes in dialogue with double quotes
message = message.replace(/'([^']+)'/g, '"$1"');

console.log(message);

output: "Hi, "What do you do for a living?," hmmm, "I am a developer""

Exercise 3
Number Again
/^[+-]?(\d+(\.\d*)?|\.\d+)([eE][+-]?\d+)?$/
