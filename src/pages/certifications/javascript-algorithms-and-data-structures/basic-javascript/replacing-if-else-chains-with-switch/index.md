---
title: Replacing If Else Chains with Switch
---
## Replacing If Else Chains with Switch

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/javascript-algorithms-and-data-structures/basic-javascript/replacing-if-else-chains-with-switch/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<h1>Replacing if statments with switch</h1>

<h2>function with if statments</h2>

function chainToSwitch(val) {
  var answer = "";
switch(val)  {
  case "bob":
  return "Marley";
  break;
  case 42:
  return "The Answer";
  break;
  case 1:
  return "There is no #1";
  break;
  case 99:
  return "Missed me by this much!";
  break;
  case 7:
  return "At Nine";
  break;
  default:
  return answer;   
  }
  
  // Only change code above this line  
  return answer;  
}

// Change this value to test
chainToSwitch(7);


<h2> Same function with switch statments</h2>
function chainToSwitch(val) {
  var answer = "";
switch(val)  {
  case "bob":
  return "Marley";
  break;
  case 42:
  return "The Answer";
  break;
  case 1:
  return "There is no #1";
  break;
  case 99:
  return "Missed me by this much!";
  break;
  case 7:
  return "At Nine";
  break;
  default:
  return answer;   
  }
  
  // Only change code above this line  
  return answer;  
}

// Change this value to test
chainToSwitch(7);
