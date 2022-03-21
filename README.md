# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (string){
  let answer = ""
  for (let character in string) {
    let newCharacter = "-"

    if (character !== "."){
      newCharacter = character
    }

    answer += newCharacter
  }

  return answer
}
```

| Input | Output |
|"Meow" | "0123" |
|Rawr.TV| "0123456"| 
|       |        | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes any inputted string and takes the indexes of each character in the string, adds it to the answer variable, and returns the indexes as a string. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
