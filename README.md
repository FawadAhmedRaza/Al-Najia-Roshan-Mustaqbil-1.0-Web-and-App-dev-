Here is a Markdown file with practice exercises for HTML covering the specified topics:

```markdown
# HTML Practice Exercises

## Tables

### Simple Table
```html
<table border="1">
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
  </tr>
  <tr>
    <td>Row 2, Cell 1</td>
    <td>Row 2, Cell 2</td>
  </tr>
</table>
```

### Colspan
```html
<table border="1">
  <tr>
    <th colspan="2">Header spanning two columns</th>
  </tr>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
  </tr>
  <tr>
    <td>Row 2, Cell 1</td>
    <td>Row 2, Cell 2</td>
  </tr>
</table>
```

### Rowspan
```html
<table border="1">
  <tr>
    <th rowspan="2">Header spanning two rows</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Row 2, Cell 2</td>
  </tr>
  <tr>
    <td>Row 3, Cell 1</td>
    <td>Row 3, Cell 2</td>
  </tr>
</table>
```

### Table Sections: `thead`, `tbody`, `tfoot`
```html
<table border="1">
  <thead>
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Row 1, Cell 1</td>
      <td>Row 1, Cell 2</td>
    </tr>
    <tr>
      <td>Row 2, Cell 1</td>
      <td>Row 2, Cell 2</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Footer 1</td>
      <td>Footer 2</td>
    </tr>
  </tfoot>
</table>
```

## Form Elements

### Input Types
```html
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" placeholder="Enter your name" required><br>

  <label for="age">Age:</label>
  <input type="number" id="age" name="age" min="1" max="100"><br>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" placeholder="Enter your email" required><br>

  <label for="phone">Phone:</label>
  <input type="tel" id="phone" name="phone" placeholder="123-456-7890"><br>

  <label for="password">Password:</label>
  <input type="password" id="password" name="password" minlength="8" required><br>

  <label for="dob">Date of Birth:</label>
  <input type="date" id="dob" name="dob"><br>

  <button type="submit">Submit</button>
</form>
```

### Radio Buttons
```html
<form>
  <p>Gender:</p>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male</label><br>

  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label><br>

  <input type="radio" id="other" name="gender" value="other">
  <label for="other">Other</label><br>
</form>
```

### Checkboxes
```html
<form>
  <p>Select your hobbies:</p>
  <input type="checkbox" id="hobby1" name="hobbies" value="reading">
  <label for="hobby1">Reading</label><br>

  <input type="checkbox" id="hobby2" name="hobbies" value="travelling">
  <label for="hobby2">Travelling</label><br>

  <input type="checkbox" id="hobby3" name="hobbies" value="cooking">
  <label for="hobby3">Cooking</label><br>
</form>
```

### Select and Option Groups
```html
<form>
  <label for="country">Country:</label>
  <select id="country" name="country">
    <optgroup label="Europe">
      <option value="germany">Germany</option>
      <option value="france">France</option>
    </optgroup>
    <optgroup label="Asia">
      <option value="japan">Japan</option>
      <option value="china">China</option>
    </optgroup>
  </select>
</form>
```

### Submit Button and Input Type Button
```html
<form>
  <button type="submit">Submit</button>
  <input type="button" value="Click me">
</form>
```

### Legend and Fieldset
```html
<form>
  <fieldset>
    <legend>Personal Information</legend>

    <label for="fname">First Name:</label>
    <input type="text" id="fname" name="fname"><br>

    <label for="lname">Last Name:</label>
    <input type="text" id="lname" name="lname"><br>
  </fieldset>
</form>
```

### Input Examples with Attributes
```html
<form>
  <label for="disabledInput">Disabled Input:</label>
  <input type="text" id="disabledInput" name="disabledInput" disabled><br>

  <label for="readonlyInput">Readonly Input:</label>
  <input type="text" id="readonlyInput" name="readonlyInput" value="Read only value" readonly><br>

  <label for="placeholderInput">Input with Placeholder:</label>
  <input type="text" id="placeholderInput" name="placeholderInput" placeholder="Enter text here"><br>

  <label for="limitedInput">Input with Max and Min:</label>
  <input type="number" id="limitedInput" name="limitedInput" min="1" max="10"><br>

  <label for="sizedInput">Input with Size:</label>
  <input type="text" id="sizedInput" name="sizedInput" size="40"><br>

  <label for="maxLengthInput">Input with Max Length:</label>
  <input type="text" id="maxLengthInput" name="maxLengthInput" maxlength="10"><br>

  <label for="nameValueInput">Input with Name and Value:</label>
  <input type="text" id="nameValueInput" name="exampleInput" value="Default value"><br>
</form>
```
```

This Markdown file covers exercises for tables, form elements, and various input attributes, providing examples for students to practice and understand HTML concepts.
