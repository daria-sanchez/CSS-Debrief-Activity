# CSS-Debrief-Activity

Skills based review for the Junior Web Developer CSS Introduction lesson.

## Directions

- When you get into your breakout room, select a team member to share their screen and record the answers the team finds
- With your Breakout Team, scroll through the CSS Code below and answer the questions in the comments
- Team members who are not sharing screen should also fill in the answers and make the changes in their own code
- Use your Google Foo skills to find the answers and explore what CSS can offer your website
- All team members should search for the answers, use the chat to send helpful links that are found
- Feel free to copy and paste useful links into comments in this file for easy reference in the future
- Communicate and work with your team to ensure all members understand the answers before you move on to answering the next question
- If you finish early, try the *BONUS* questions at the bottom of the file, and/or explore any concepts you come across that you find interesting or want to learn more about!
- HAVE FUN! :)

### Activity

## Part 1 - Clone the project

* Begin by _forking_ this project into a personal repository.
  * To do this, click the `Fork` button located at the top right of this page.
* Navigate to your github profile to find the _newly forked repository_.
* Clone the repository from **your account** into the directory on your computer that you use to keep your projects (ex. `dev` directory).
* Open the newly cloned project in a code editor (ex. Visual Studio Code).

### Part 2 - Edit the _cloned_ project

* from a text editor (i.e. - Visual Studio Code), select:
  * `File` > `Add Folder to WorkSpace`
    * Select the directory you use to store your projects (ex. `dev` directory)
    * From the text editor,in the directory you use to store your projects (ex. `dev` directory), locate the newly cloned project
    * Expand the project from the _project explorer (may just be called `explorer`)_
    * Modify the `index.html` and `style.css` per the directions provided.

1. Open in browser/live server so you can see your changes

2. Start by linking your css file to your html file

3. Add a universal selector at the top of the CSS file (`*`), and within that ruleset -- add a property of `box-sizing` with a value of `border-box`

4. Let's change the font on the page to be more modern. Go to the Google Fonts website and find the `'Open Sans'` font. Select all of the styles, and then paste the stylesheet link in the html, above the local CSS file.

5. In the body selector rule, add a font-family property with a value of `'Open Sans', sans-serif`

6. Let's change the background of the body. Replace the background-color property with the `background-image property`. Add a value of `linear gradient` with `whitesmoke` as the first value, and `rgb(35, 47, 58)` as the second value.

7. Convert `padding` property on `li a` rule to shorthand

8. Add a `text-align` property with a value of `center` to the same `li a` ruleset.

9. Add Add a `text-align` property with a value of `center` to the `.center-title` class selector.

10. Add a `width` property with the value of `50%` to the `figure` selector.

11. Add a `flex-direction` property with a value of column to the `section`, `#about-sec`, and `figure` selectors.

12. In the `aside` element selector ruleset:

  - Use the shorthand `border` property to add a `white 4px double` border
  - Add a `margin` property and set the values to reflect `1em` on the top and bottom, and the sides to `auto`;
  - Add a `color` property, with a value of `rgb(35, 47, 58)`
  - Add a `background-color` of `rgb(95, 211, 249)`

13. Add an `aside p` element selector directly underneath the `aside` selector, above the `#concert-schedule-sec`:

  - Add a `font-weight` property with a value of `600`
  - and a `font-size` property with a value of `1.25em`
  - Add a `background-color` property, with a value of `rgb(191, 133, 25)`
  - Add a `color` property, with a value of `whitesmoke`
  - Add a `padding` property, with a value of `0.75em` on all sides
  - Add a `margin` property, with a value of `0`
  - Add a `text-transform` property, with a value of `uppercase`
  - Add a `border-bottom` of `4px double white`

14. Add an `aside ul li a` element selector directly underneath the `aside p` selector, above the `#concert-schedule-sec`:

  - Add a `text-align` property with a value of `justify`
  - and a `padding` property with a value of `0`
  - Add a `color` property, with a value of `rgb(35, 47, 58)`
  - Add a `text-decoration` property, with a value of `underline`
  *We'll come back and link it to a list of movies he's been in later

15. Add an `aside ul` element selector directly underneath the `aside p` selector, above the `aside ul li a`:

  - Add a `font-size` property with a value of `0.9em`
  - Add a `margin` of `1em` on all sides
  - Add a `padding` property of `0` on the top and bottom, `0.75em` on the right, and `1em` on the left

16. Add a `figcaption` element selector ruleset directly underneath the `figure` selector.

17. In the figcaption ruleset:

  - Add a property-value pair that will `make the text italic`
  - Add a `background color` property and set the value to `rgba(35, 47, 58)`
  - Set the `color` of the figcaption text to `whitesmoke`
  - Using the `padding shorthand` property, add `0.25em` of padding on all sides
  - Add an `opacity` property, and set the value to `0.5`
  - Add a `font-size` property, and set the value to 0.85em;

18. Around line 55, locate the `#about-sec` selector, directly below that, and above the `#about-sec div` selector, add an `#about-sec h2` ruleset:

  - Add a `font-size` property, with a value of 1.95em
  - and a `padding` property, with a value of `0 1.5em`

19. Directly below the `#about-sec h2` ruleset, add an `#about-sec #about-blurb` ruleset:

  - Add a `padding` property, with a value of `0 2.5em`

Last: Modify the colors, borders, and transitions however you like to make the page look more legit!



### Part 3 - _Pushing_ new changes to repository

* From a _terminal_ navigate to the root directory of the _cloned_ project.
* From the root directory of the project, execute the following commands:
  * `git add .`
    * Add all files in current directory to the staging area
  * `git commit -m 'I have made an edit to a file!'`
    * Save all staged changes to local repository
  * `git push -u origin main`
    * Push changes from local repository to remote repository

### Part 4 - Submitting assignment

* From the browser, navigate to the _forked_ project from **your** Github account.
* Click the `Pull Requests` tab.
* Select `New Pull Request`

### Resources

- <https://www.w3schools.com/css/css_intro.asp>
- <https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS>

- <https://www.codecademy.com/learn/learn-intermediate-css/modules/layout-with-flexbox/cheatsheet>
