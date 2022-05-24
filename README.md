# CSS-Debrief-Activity

Skills based review for the Junior Web Developer CSS Introduction lesson.

### Directions

- When you get into your breakout room, select a team member to share their screen and record the answers the team finds
- With your Breakout Team, scroll through the CSS Code below and answer the questions in the comments
- Team members who are not sharing screen should also fill in the answers and make the changes in their own code
- Use your Google Foo skills to find the answers and explore what CSS can offer your website
- All team members should search for the answers, use the chat to send helpful links that are found
- Feel free to copy and paste useful links into comments in this file for easy reference in the future
- Communicate and work with your team to ensure all members understand the answers before you move on to answering the next question
- If you finish early, try the *BONUS* questions at the bottom of the file, and/or explore any concepts you come across that you find interesting or want to learn more about!
- HAVE FUN! :)

## Activity

## Part 1 - Fork & Clone the project

* Begin by _forking_ this project into a personal repository.
  * To do this, click the `Fork` button located at the top right of this page.
* Navigate to your github profile to find the _newly forked repository_.
* Clone the repository from **your account** into the directory on your computer that you use to keep your projects (ex. `dev-projects` directory).
* Open the newly cloned project in a code editor (ex. Visual Studio Code).

### Part 2 - Edit the _cloned_ project

* from your text editor (i.e. - Visual Studio Code), select:
  * `File` > `Add Folder to WorkSpace`
  * Select the directory you use to store your projects (ex. `dev-projects` directory)
  * From the text editor,in the directory you use to store your projects (ex. `dev-projects` directory), locate the newly cloned project
  * Expand the project from the _project explorer (may just be called `explorer`)_
  * Modify the `index.html` and `assets/css/style.css` per the directions provided.

#### Setup

1. Open in browser/live server so you can see your changes in real time and notice how the code morphs the `live browser page`

2. Start by linking your css file to your html file

#### Reset CSS Styling

3. Add a universal selector at the top of the CSS file (`*`), and within that ruleset -- add a property of `box-sizing` with a value of `border-box`

#### Typography

4. Change the font on the page to be more modern.
		- Go to the [Google Fonts website](https://fonts.google.com) and find the `'Open Sans'` font.
		- Open the font, and select: 'Light 300', Light 300 Italic', 'Regular', 'Regular 400 Italic', 'SemiBold 600', 'SemiBold 600 Italic', 'Bold 700', 'Bold 700 Italic'
		- Copy the entire ```<link rel=...stylesheet">``` link in the pop-up side menu (you may have to widen your screen to view). Then paste the stylesheet link in the index.html, above the local CSS file.
		- Copy the entire `font-family rule`, and paste in Step 5.

5. In the `body` selector ruleset, add a font-family property with a value of `'Open Sans', sans-serif`

#### Style

6. On the same `body` selector, replace the `background-color property` with the `background-image property`. Add a value of `linear gradient` with `whitesmoke` as the first value, and `rgb(35, 47, 58)` as the second value.

7. Convert the `padding` property on the `li a` ruleset to the shorthand syntax;

8. Add a `text-align` property with a value of `center` to the same `li a` ruleset.

9. Add Add a `text-align` property with a value of `center` to the `.center-title` class selector.

10. a. Navigate to the `index.html` and remove the `width` attribute

10. b. Add a `width` property with the value of `30%` to the `figure` selector.

11. Add a `flex-direction` property with a value of column to the `section`, `#about-sec`, and `figure` selectors.

12. In the `aside` element selector ruleset:

	- Use the shorthand `border` property to add a `4px double black` border
	- Add a `margin` property and set the values to reflect `1em` on the top and bottom, and the sides to `0`;
	- Add a `color` property, with a value of `rgba(35, 47, 58, 0.05)`
	- Add a `background-color` of `rgba(35, 47, 58, 0.05)`

13. Add an `aside p` element selector directly underneath the `aside` selector, above the `#concert-schedule-sec`:

	- Add a `font-weight` property with a value of `600`
	- and a `font-size` property with a value of `1.25em`
	- Add a `background-color` property, with a value of `rgb(35, 47, 58)`
	- Add a `color` property, with a value of `whitesmoke`
	- Add a `padding` property, with a value of `0.5em` on all sides
	- Add a `margin` property, with a value of `0`
	- Add a `text-transform` property, with a value of `uppercase`
	- Add a `border-bottom` of `4px double rgba(0, 0, 0, 0.77)`
	- Add an `opacity` property, with a value of `0.6`

14. Add an `aside ul li a` element selector directly underneath the `aside p` selector, above the `#concert-schedule-sec`:

	- Add a `text-align` property with a value of `justify`
	- and a `padding` property with a value of `0`
	- Add a `color` property, with a value of `rgb(35, 47, 58)`
	- Add a `text-decoration` property, with a value of `underline`


15. Add an `aside ul` element selector directly underneath the `aside p` selector, above the `aside ul li a`:

	- Add a `font-size` property with a value of `0.9em`
	- Add a `margin` of `1em` on all sides
	- Add a `padding` property of `0` on the top and bottom, `0.75em` on the right, and `1em` on the left

16. Add a `figcaption` element selector ruleset directly underneath the `figure` selector.

17. In the figcaption ruleset:
	- Add a `property-value pair` that will `make the text italic`
	- Add a `background color` property, and set the value to `rgba(35, 47, 58)`
	- Set the `color` of the figcaption text to `whitesmoke`
	- Using the `padding shorthand` property, add `0.25em` of padding on all sides
	- Add an `opacity` property, and set the value to `0.5`
	- Add a `font-size` property, and set the value to `0.85em`;

18. Around line 55, locate the `#about-sec` selector, directly below that, and above the `#about-sec div` selector, add an `#about-sec h2` ruleset:
	- Add a `font-size` property, with a value of `1.95em`
  	- and a `padding` property, with a value of `0 1.5em`

19. Directly below the `#about-sec h2` ruleset, add an `#about-sec #about-blurb` ruleset:
	- Add a `padding` property, with a value of `0 2.5em`

20. Locate the `Table - Concert Schedule` in both the `index.html` and `style.css`, as well as in the `browser`

21. In the `#concert-schedule-sec` ruleset:
	- Add a `color` property, and a value of `rgb(255, 54, 154)`
	- Add a `background-color` property, with a value of `black`
	- Replace the `max-width` property with the `width` property, and set the value to `100vw`
	- Add a `padding` property with a value of `2em`;

22. Add a `#concert-schedule-sec h3` element selector ruleset directly underneath the last selector.
	- Add a `font-size` property with a value of `2em`;

Last: Continue to modify the colors, borders, and transitions however you like with the remaining elements! Experiment with positioning, margins, padding, user-experience, etc.

*** BONUS ***

* Find a website with a list of the movies Harry Styles has been in and hyperlink it to the `See Movies` a tag. Can you get the link to open in a new tab?
* Link the navigation list items to jump to the corresponding section on the page


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
