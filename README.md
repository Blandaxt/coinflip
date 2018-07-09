# coinflip
Coin flip is a basic random number generator game that chooses either heads or tails base on parameters i set such as (<, >) the greater or less than or (=) equal. This game allows the user to click a button. After clicking that button, the user expects one of two strings to show. Heads or Tails! 

## How it's made: 

*Tech used:* HRML, JavaScript and Node.js. 

1. I first created my HTML file to include a button tag for the click event, a span tag to display the results and a script tag to code my javascript.

2. Then i created my Node.js file so i can host my project. I set that server on port 8000. 

3. Then i made sure to include my HTML file name under the readFile method. And set the content type to be text.

## Dependencies: 

install this npm module: 
*npm i -g http-server*

**(- i is short for install. -g, option g, will install the package
globally, giving us a http-server command line tool.)**

### Runing: 

You can run this file after downloading it by going in your terminal and typing http-server -p 8000 to run it on port 8000. 

## Optimization: 

If i had more time, i would have created a CSS file and linked it to my project so that is can look better visually. i would also have switched out the heads or tails string to an image like a quarter that has heads or tails displaying base on the if parameters from the random number generator. 
