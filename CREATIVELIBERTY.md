# My Personal Formatting Cheat Sheet

## 1. Headings
This is how you write a heading. You use a single hashtag (#) followed by a space at the start of the line. This is an H1 heading.

## This is a Sub-heading (H2)
This is how you write a sub-heading. You use two hashtags (##) followed by a space. You can use up to six hashtags to keep making the headings smaller!

For example:
### This is an H3 Heading
You use three hashtags (###). This is used for sub-sections underneath an H2.

#### This is an H4 Heading
You use four hashtags (####). 

##### This is an H5 Heading
You use five hashtags (#####). 

###### This is an H6 Heading
You use six hashtags (######). This is the absolute smallest heading size you can make in Markdown.

---

## 2. Text Formatting Syntax

**This is Bold Text**
This is how you write bold text, you wrap your word or sentence in double asterisks (**).

*This is Italic Text*
This is how you write italic text, you wrap your word or sentence in a single asterisk (*).

~~This is Crossed Out Text~~
This is how you create crossed out (strikethrough) text, you wrap your word or sentence in double tildes (~~).

<u>This is Underlined Text</u>
This is how you underline text. Because standard Markdown doesn't have a symbol for this, you have to use HTML tags. You type `<u>` before the word, and `</u>` after the word.

<mark>This is Highlighted Text</mark>
This is how you highlight text like a yellow marker using the HTML `<mark>` tag.

---

## 3. Lists and Organization

* This is a bullet list item
* This is another item
This is how you write a bulleted list, you use a single asterisk (*), a dash (-), or a plus sign (+) followed by a space.

1. This is a Numbered List
2. Here is the second item
This is how you create a numbered list, you just type a number, a period, and a space (1. ).

- [x] This is a completed task
- [ ] This is an uncompleted task
This is how you create a checkbox list. You type a dash, a space, and brackets `[ ]` for an empty box, or `[x]` for a checked box.

> This is a Block Quote
This is how you write a block quote, you use a greater-than sign (>) followed by a space.

---

## 4. Advanced Creative Elements

### Tables
This is how you create a table to organize data. You use pipes (`|`) and dashes (`-`) to separate columns and rows.
| Technology | Focus Area |
| :--- | :--- |
| SQL | Database Management |
| Node.js | Backend Development |

### Syntax Highlighting in Code Blocks
If you add the name of a programming language right after the top three backticks, GitHub will color-code the syntax inside the block!

```javascript
console.log("Setting up the workspace environment");

### Keyboard Inputs
This is how you make text look like a physical button on a keyboard using the HTML `<kbd>` tag.

Press <kbd>Ctrl</kbd> + <kbd>Space</kbd> to open code suggestions in your editor.

---

### Collapsible Sections (Dropdowns)
This is how you hide text inside a clickable dropdown menu to keep your file clean!

<details>
<summary>Click here to reveal a secret</summary>
Surprise! You can hide long notes or entire lists inside this dropdown.
</details>

---

### Clickable Links
[This is a Clickable Link](https://github.com)

This is how you create a link. You wrap the text you want people to read in square brackets `[ ]`, and immediately put the website URL in parentheses `( )` right next to it with no spaces.