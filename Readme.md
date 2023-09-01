# index.html
first we have div that contains one more div inside and inside of that we have a <h1> tag which holds the text 
then we a button which hols rs as a text value 
then we have used <select> and <option >tag that hold a list of items of service quality

after that we have an input box which is for people sharing the bill 
then we have a button called calculate which holds a function call of javascript

# index.js
in this functionality part we are selecting all the items from html whith queryselector 
then we have a function called calculate  then we are checking the value by
 <!-- const tip = ((amount.value * quality.value) / (guests.value)).toFixed(2); -->
 this is for tip amount according to guests and payment 

  then we are checking the condition that if number is nan than tip amount will be 0 
  else the tip amount will be calculated and shown by the function showTipAmount()

  we have used set timeout function to display the the amount for 3 second and also done with some animation part of css