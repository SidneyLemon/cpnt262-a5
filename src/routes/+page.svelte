<script>
  import { browser } from "$app/environment";

  let firstNum = 0;
  let secondNum = 0;
  let thirdNum = 0;

  if (browser) {
    firstNum = prompt("Please enter any number of your choosing");
    secondNum = prompt("enter another number");
    thirdNum = prompt("last one!");
  }
</script>

<main>
  <h1>Assignment 5 - Loops and arrays</h1>
  <p>{firstNum}, {secondNum}, {thirdNum}</p>
</main>
