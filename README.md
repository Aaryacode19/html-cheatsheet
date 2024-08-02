# HTML-Cheatsheet
## Complete HTML Reference
For a comprehensive reference on HTML elements, attributes, and usage examples, visit the **[Mozilla Developer Network (MDN) HTML Element Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)**.

## HTML Boilerplate
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Description of the page">
    <meta name="keywords" content="HTML, CSS, JavaScript">
    <meta name="author" content="Your Name">
    <title>Document</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    
</body>
</html>
```

## HTML Elements

### Headings

```html
<h1>This is a Heading 1</h1>
<h2>This is a Heading 2</h2>
<h3>This is a Heading 3</h3>
<h4>This is a Heading 4</h4>
<h5>This is a Heading 5</h5>
<h6>This is a Heading 6</h6>
```

### Paragraph

```html
<p>This is a paragraph.</p>
```

### Links

```html
<a href="https://www.example.com">This is a link</a>
```

### Images

```html
<img src="image.jpg" alt="Description of image">
```

### Lists

#### Unordered List

```html
<ul>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3</li>
</ul>
```

#### Ordered List

```html
<ol>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3</li>
</ol>
```

### Tables

```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>
```

### Forms

```html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    
    <input type="submit" value="Submit">
</form>
```

### Buttons

```html
<button type="button">Click Me!</button>
```

### Divisions and Spans

#### Division

```html
<div>This is a division element.</div>
```

#### Span

```html
<span>This is a span element.</span>
```

### Semantic Elements

```html
<header>This is a header.</header>
<nav>This is a navigation bar.</nav>
<main>This is the main content area.</main>
<article>This is an article.</article>
<section>This is a section.</section>
<aside>This is a sidebar.</aside>
<footer>This is a footer.</footer>
```

## HTML Attributes

### `id` Attribute

```html
<p id="unique-paragraph">This paragraph has a unique id.</p>
```

### `class` Attribute

```html
<p class="common-class">This paragraph has a class.</p>
<p class="common-class another-class">This paragraph has multiple classes.</p>
```

### `name` Attribute

```html
<input type="text" name="username" placeholder="Enter your username">
<input type="email" name="email" placeholder="Enter your email">
```

### `title` Attribute

```html
<p title="Tooltip text">Hover over this paragraph to see the tooltip.</p>
```

### `alt` Attribute

```html
<img src="image.jpg" alt="Description of the image">
```

### `href` Attribute

```html
<a href="https://www.example.com">This is a link</a>
```

### `src` Attribute

```html
<img src="image.jpg" alt="Description of the image">
<script src="script.js"></script>
```

### `placeholder` Attribute

```html
<input type="text" placeholder="Enter your name">
```

### `value` Attribute

```html
<input type="text" value="Initial value">
<input type="submit" value="Submit">
```

### `disabled` Attribute

```html
<input type="text" disabled>
<button disabled>Disabled Button</button>
```

### `checked` Attribute

```html
<input type="checkbox" checked>
<input type="radio" name="option" checked>
```

## Form Elements and Input Types

### Form Elements

#### `<form>`

```html
<form action="/submit" method="post">
    <!-- Form elements go here -->
</form>
```

#### `<textarea>`

```html
<textarea id="message" name="message" rows="4" cols="50" placeholder="Enter your message"></textarea>
```

#### `<select>` and `<option>`

```html
<label for="cars">Choose a car:</label>
<select id="cars" name="cars">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
    <option value="mercedes">Mercedes</option>
    <option value="audi">Audi</option>
</select>
```

#### `<button>`

```html
<button type="button">Click Me!</button>
<button type="submit">Submit</button>
```

#### `<fieldset>` and `<legend>`

```html
<fieldset>
    <legend>Personal Information</legend>
    <label for="fname">First name:</label>
    <input type="text" id="fname" name="fname">
    <label for="lname">Last name:</label>
    <input type="text" id="lname" name="lname">
</fieldset>
```

#### `<label>`

```html
<label for="username">Username:</label>
<input type="text" id="username" name="username">
```

### Input Types

#### Text Input

```html
<input type="text" id="username" name="username" placeholder="Enter your username">
```

#### Password Input

```html
<input type="password" id="password" name="password" placeholder="Enter your password">
```

#### Email Input

```html
<input type="email" id="email" name="email" placeholder="Enter your email">
```

#### Number Input

```html
<input type="number" id="quantity" name="quantity" min="1" max="10">
```

#### Date Input

```html
<input type="date" id="birthday" name="birthday">
```

#### Checkbox

```html
<input type="checkbox" id="subscribe" name="subscribe" value="newsletter">
<label for="subscribe">Subscribe to newsletter</label>
```

#### Radio Button

```html
<input type="radio" id="male" name="gender" value="male">
<label for="male">Male</label>
<input type="radio" id="female" name="gender" value="female">
<label for="female">Female</label>
```

#### File Input

```html
<input type="file" id="myfile" name="myfile">
```

#### Submit Button

```html
<input type="submit" value="Submit">
```

#### Reset Button

```html
<input type="reset" value="Reset">
```

#### Button

```html
<input type="button" value="Click Me!">
```

### Example Form with Various Input Types

```html
<form action="/submit" method="post">
    <fieldset>
        <legend>Personal Information</legend>
        
        <label for="fname">First name:</label>
        <input type="text" id="fname" name="fname" placeholder="Enter your first name">
        
        <label for="lname">Last name:</label>
        <input type="text" id="lname" name="lname" placeholder="Enter your last name">
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email">
        
        <label for="birthday">Birthday:</label>
        <input type="date" id="birthday" name="birthday">
        
        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>
        
        <label for="cars">Choose a car:</label>
        <select id="cars" name="cars">
            <option value="volvo">Volvo</option>
            <option value="saab">Saab</option>
            <option value="mercedes">Mercedes</option>
            <option value="audi">Audi</option>
        </select>
        
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" cols="50" placeholder="Enter your message"></textarea>
        
        <label for="subscribe">Subscribe to newsletter:</label>
        <input type="checkbox" id="subscribe" name="subscribe" value="newsletter">
        
        <label for="myfile">Upload a file:</label

>
        <input type="file" id="myfile" name="myfile">
        
        <input type="submit" value="Submit">
        <input type="reset" value="Reset">
    </fieldset>
</form>
```

## HTML Entity Codes

HTML allows you to represent special characters and symbols using entity codes. For a comprehensive list of named character references, refer to the [HTML Named Character References](https://html.spec.whatwg.org/multipage/named-characters.html) specification.

This specification provides a detailed list of entity codes for characters like `<`, `>`, `&`, quotation marks, special symbols, and more. Using entity codes ensures that characters display correctly across different browsers and devices.

For example:
- `&lt;` represents `<`
- `&gt;` represents `>`
- `&amp;` represents `&`
- `&quot;` represents `"`
- `&euro;` represents €

For a complete reference, visit the [HTML Named Character References](https://html.spec.whatwg.org/multipage/named-characters.html) page.
Sure! Here's a short message you can use for your GitHub repo:

---

# Contribute to this Cheatsheet!

Welcome to our cheatsheet repository! We encourage contributions from everyone. Whether you want to add new tips, improve existing ones, or fix any errors, your help is appreciated. 

Feel free to fork this repo, make your changes, and submit a pull request. Let's make this cheatsheet better together!

Happy coding!
