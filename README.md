# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (currentColor){
  if (currentColor === "green"){
    nextColor = "yellow"
  } else if (currentColor === "yellow"){
    nextColor = 'red'
  } else if (currentColor === "red"){
    nextColor = 'green'
  }

  return nextColor
}
```

|    Input    |           Output           |
| ----------- | -------------------------- |
|   yellow    |           red              | 
|   green     |           yellow           | 
|   orange    |    Orange is undefined     | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>
      This program has essentially created a looping color sequence of green then 
      yellow then red and will take any of those strings as the value passed to it 
      and then return the next color in the sequence. It does not however have a 
      get out for if the color variable passed to it is not one of the three.
    </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
