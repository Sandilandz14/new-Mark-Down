# What is a Mark Down
## Sub-heading
### Level 3 heading
### Level 3 heading
#### Level 4 heading
##### Level 5 heading
###### Level 6 heading

MArkdown is awesome.

*Markdown supports paragraphs and  line breaks.*  
**This will be on a new line.**

## Hyperlinks in markdown

Here is a hyperlink: [Go to Wikipedia](http://en.wikipedia.org)

## Images in MD
[![some image](image.jpeg)](https://www.earth.org)
[![another image](smiling.jpeg)](https://www.earth.org)

### Emphasizing Text in Markdown
This is normial text in Markdown  
_This is a new line_

*__This one should be bold and in italics.__*

## Lists in Mark Down
###### Unordered List
- item 1
- item 2
- item 3
    - sub item 1
    - sub item 2
- item 4

###### Ordered List

1. item 1
2. item 2
    1. sub item 1
    2. sub item 2
3. item 3

## Adding Blockquotes in MD

>this is some quoted text
>
>next line
>
>>nested text

## Code blocks in Mark download:
- __HTML__

```html
<html>
<head>
<title>Codeblock Title</title>
</head>
<body>
<header></header>
<ul></ul>
<footer></footer>
</body>
</html>
```
- __Javascript__
```javascript
const thisYear = parseInt(prompt('Enter current year: '));
const birthYear = parseInt(prompt('Enter birth year: '));
function getAge(currentYear, birthYear) {
    currentAge = birthYear - currentYear;
    console.log(`Your current age is ${currentAge} years`);
    return;
};
```
- __Python__
```python
def my_age(): 
    current_year = int(input("Enter current year: "))
    birth_year = int(input("Enter birth year: "))
    current_age = current_year-birth_year
    return current_age
    print('Your current age is:', current_age)
```

## In-line code:

here is an `<img>` tag

## Escaping characters in MD:

- escape this => *
    - \*hello world\*

## HTML MArkdown: Raw HTML code 

<img src="smiling.jpeg" alt="image">
