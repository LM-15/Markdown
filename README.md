# Markdown

## Contents exxample (get the link by hovering over the link (not in edit mode), right clicking, and copying the link)
* [What is it](https://github.com/LM-15/Markdown/blob/main/README.md#what-is-it)

## What is it?
* Way to stylize text on the web (a free text to HTML conversion tool)
* Here, you can click on the `Raw` button above to see the Markdown syntax without having to edit.
* Can use in many places in Github: gists (repositories to share your ideas with others?); comments in issues and pull requests; files with .md or .markdown extensions
* GitHub.com has some syntax of its own that provides an additional features, many of which make it easier to work with content on GitHub.com.  
   * > Note that some features of GitHub Flavored Markdown are only available in the descriptions and comments of Issues and Pull Requests. These include @mentions as well as references to SHA-1 hashes, Issues, and Pull Requests. Task Lists are also available in Gist comments and in Gist Markdown files.

## Headings:
* Use 1 to 6 hashmarks to changes the sizes:
  * # Largest
  * ## Second largest
  * ###### Smallest

## Styling text:
* Italic
  * *an asterisk or underscore in front and at the end of text (no spaces)*
* Bold
  * **2 asterisks or 2 underscores in front and at the end of text (no spaces)**
* Strikethrough
  * ~~2 tildes in front and at the end of text (no spaces)~~
* Ignore markdown symbols by putting back slashes in front of each symbol, e.g.:
  * It is \*high time\*

## Unordered lists:
* One asterisk or dash in front of each line in the list; put a space between the asterisk or dash and the text
  * If you want to nest elements of the list, add spaces until the cursor is under the text of the bullet above, then add the asterisk, a space and the text
  * and another nested
* and another
  
## Ordered lists
1. "1." in front of each line in the list; put a space between the "1." and the text
   1. If you want to nest elements of the list, add spaces until the cursor is under the text of the bullet above, then add the "1.", a space and the text
   1. and another nested
1. and another

## Links to URLs:
* Put the link text in brakets, then paste the URL in parentheses right after that with no spaces:
  * [Fun, seasonal Demilked link](https://www.demilked.com/upcycling-old-doll-houses-samantha-browning/)
* Or just paste the full URL: https://www.demilked.com/upcycling-old-doll-houses-samantha-browning/

## Quoting
* Quote text with a greater than sign:
  * In the words of Vincent Price:
  * > It is as much fun to scare as to be scared.
* Quote a command/code using single backticks before and after a piece of text:
  * Use the `Instances` table to...

## Add tables:
Add a list of column headers separated (and surrounded) by subfield markers; then in next row add hyphens and subfield markers to separate the headers from the content (can be just 3), then add content separated by subfield markers.  Can use "<br>" to start a new line in the same cell.:

|Halloween candy|Rating|
|---|---|
|Payday Bar|Favorite|
|Twizlers |OK|
|Mars Bar |OK|
|Peanut Butter cup|Second most likely to be stollen by family members when you are not looking; hide these securely.  May be traded for three times lesser candies.|
|1,000,000 dollar bars|Very rare.|

## Username @mentions
* Type an at symbol followed by a user or team name to notify a person to review a comment
  * @LM-15
  
## Make a collapsable list
<details>
  <summary>Click to expand!</summary>
  
  ### Heading
  1. A numbered
  2. List
     * with some
     * sub bullets
     </details>
     

## More info:
* [Github's Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* [GitHub's Basic writing and formatting syntax](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax)
* [GitHub's Keyboard shortcuts](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/keyboard-shortcuts)
