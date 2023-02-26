## css tutorial
### Syntax
<div align=center>
  <img src="https://www.w3schools.com/css/img_selector.gif" alt="image" style="width:60%;text-align:center" />
</div>

### Selector
<table class="selector" style="margin: 20px 0; text-align: left !important">
  <tbody>
    <tr style="font-weight:bold">
      <th>Selector</th>
      <th>Example</th>
      <th>Example Striped</th>
    </tr>
    <tr>
      <td>#id</th>
      <td>#firstname</th>
      <td>Selects the element with id="firstname"</th>
    </tr>
    <tr>
      <td>.class</th>
      <td>.intro</th>
      <td>Selects all elements with class="intro"</th>
    </tr>
    <tr>
      <td>element.class</th>
      <td>test.intro</th>
      <td>Selects only <test> elements with class="intro"</th>
    </tr>
    <tr>
      <td>*</th>
      <td>*</th>
      <td>Selects all elements</th>
    </tr>
    <tr>
      <td>element</th>
      <td>test</th>
      <td>Selects all <test> elements</th>
    </tr>
    <tr>
      <td>grouped elements</th>
      <td>test1, test2</th>
      <td>Selects all <test1> elements and all <test2> elements</th>
    </tr>
  </tbody>
</table>

### How To Add CSS
* External CSS
* Internal CSS
* Inline CSS
* Multiple Style Sheets
If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used. 
* Cascading Order
All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:
  1. Inline style (inside an HTML element)
  2. External and internal style sheets (in the head section)
  3. Browser default
### CSS Comments
A CSS comment is placed inside the <style> element, and starts with /* and ends with */:

### CSS Colors

