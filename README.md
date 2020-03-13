**freeCodeCamp** - Quality Assurance American / British English Translator
------

### User stories:

1. I can enter a simple sentence into the text area and select whether to translate to British or American English from the dropdown menu.
2. When the "Translate" button is pressed:
    * Append the translated sentence to the `translated-sentence` `div`. See the JavaScript files in `/public` for the different spelling and terms your application should translate.
    * Wrap any translated terms or spelling with `<span class="highlight">...</span>` tags so they appear in green.
    * If the sentence in the text area has no terms or spelling that should be translated, append the message "Everything looks good to me!" to the `translated-sentence` `div`.
    * If there is no text in the text area, append the message "Error: No text to translate." to the `error-msg` `div`.
3. I can press the "Clear Input" button to remove all text from the text area and the `translated-sentence` `div`.
4. All 12 unit tests are complete and passing. See `/tests/1_unit-tests.js` for examples of sentences you can use to write these tests.
5. All 4 functional tests are complete and passing.

### Testing and additional notes

* To run the tests on Glitch, set NODE_ENV to `test` without quotes.
* To run the tests in the console, use the command `npm run test`. To open the Glitch console, first click "Tools" in the bottom left corner and then click "Full Page Console".
* All logic can go into `public/translator.js`.
* Create all of the unit/functional tests in `tests/1_unit-tests.js` and `tests/2_functional-tests.js`.
