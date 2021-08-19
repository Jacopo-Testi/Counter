# Counter
Increment/Decrement Counter Button
This JavaScript application allows the user to increase and decrease the value of the counter.
As soon as the user enters the page, he will see 0 as the value of the counter and will have two buttons +/- to change the value of the counter.

![Counter img](https://user-images.githubusercontent.com/83421064/130104091-43ac8d05-484b-4131-aedc-875367acf1dd.png)

Project Description
The +/- buttons, and also the display of the counter value have been implemented with JavaScript.
The Javascript files starts with the declaration of 3 let variables equal to a document.querySelector: one for + button, one for the - button, one for the quantity of the counter.

![variables declaration](https://user-images.githubusercontent.com/83421064/130105915-a5c07a5c-9726-46aa-9d6f-3529a8fb04a0.png)

After that I've made an addEventListener so that as soon as the user press the plus button it will increment the quantity by one, then another addEventListener for the minus button with the implementation of an if statement in order to avoid dropping below zero in the quantity counter.

![if-statement](https://user-images.githubusercontent.com/83421064/130106458-1b180f5b-2c6f-466d-9225-8c43fc3bf90f.png)

The styling is made with pure CSS without any usage of preproccessors like SASS.
Every single file is properly dividev from one another.
