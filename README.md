# cloud-workshop
Materials for workshop about cloud development


# Exercises

## 01. Create application skeleton

Create H1 header with title of application.
Add div tag with English word.
Add 4 buttons tags with Czech translation.

## 02. Fix diacritics

Add necessary header in order to display diacritics correctly.

## 03. Add Twitter bootstrap

Add Twitter bootstrap CDN to header to make app nicer

- http://getbootstrap.com/getting-started/

## 04. Change 4 divs to buttons

Change 4 Czech options to 4 buttons. Replace div tag by button tag and class.

## 05. Use Twitter style of buttons

Add CSS class definition to buttons: class="btn btn-default".

Fix for C9.io ide to avoid jQuery warning, add /* global $ */

- https://community.c9.io/t/being-flagged-as-not-defined-in-js-file-when-using-jquery/4231/5

## 06. Display alert when on button click

Add JavaScript using jQuery and display alert after any button click.

- https://code.jquery.com/
 
## 07. Display alert with value of clicked button

We need to know what is value of clicked button. Find it and display it.

## 08. Display alert with success or fail

Compare value from clicked button and display alert with fail or success.

## 09. Status message

Add div with id "status" and set its "text" value instead of display alert.

- http://api.jquery.com/text/

## 10. Status icon

Display icon which indicates status. Use Twitter Glyphicons.

- http://getbootstrap.com/components/
- http://api.jquery.com/addClass/
- http://api.jquery.com/removeClass/

## 11. Add support for more words

Create two lists of words. One in English and one in Czech.

var czechWords = [];
var englishWords = [];

## 12. Pick random English word from list

Select random word and display it on sreen.
Use Math.random and Math.floor functions.

- http://www.w3schools.com/jsref/jsref_random.asp

## 13. Check correct answer

Compare index of selected word with primary word and display success or failure.

## 14. Generate content of buttons

Define ID for each button and use "for" cycle to display words on buttons

## 15. Generate new words after selecting correct one

Run function for generating word again when the word was correct.

## 16. Add delay before moving starting new round of game

Use setTimeout function to invoke new game after selecting word.

- http://stackoverflow.com/questions/10860171/run-function-after-delay
 
## 17. Fade out status message

Use fadeOut function to remove message from display.

- http://api.jquery.com/fadeOut/

## 18. Display message evan after fadeout

Bring back message tag using "show" function.

- http://stackoverflow.com/questions/13228696/re-displaying-after-fadeout
