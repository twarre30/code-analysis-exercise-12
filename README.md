
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

| Input | Output |
| ----- | ------ |
|       |        | 
|       |        | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td></td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible

## Inputs and Outputs

| Inputs | Outputs |
| :---: | :---: |
| yellow | red |
| red | green |
| green | yellow |



## for input yellow

for currentColor is yellow than it skips the first one and stops at the second and return red.

```js

const currentColor = yellow;

function (currentColor){
  if (currentColor === "green"){			// false
    nextColor = "yellow"
  } else if (currentColor === "yellow"){		// true
    nextColor = 'red'
  } else if (currentColor === "red"){			// does not run
    nextColor = 'green'
  }

  return nextColor					// red
}

```


## for input red

for currentColor is red than it skips the first and second one and stops on the three one to return yellow.

```js

const currentColor = red;

function (currentColor){
  if (currentColor === "green"){			// false
    nextColor = "yellow"
  } else if (currentColor === "yellow"){		// false
    nextColor = 'red'
  } else if (currentColor === "red"){			// true
    nextColor = 'green'
  }

  return nextColor					// green
}

```


## for input green

for currentColor is green than it  would stop with the first one and return nextColor is yellow.

```js

const currentColor = green;

function (currentColor){
  if (currentColor === "green"){			// true
    nextColor = "yellow"
  } else if (currentColor === "yellow"){		// does not run	
    nextColor = 'red'
  } else if (currentColor === "red"){			// does not run
    nextColor = 'green'
  }

  return nextColor					// yellow
}

```

## Summary

As long as the currentColor equals the color listed then it would stop and display nextColor,
as is the function of a stop light. If a different color not listed above should display as undefined.

 
