# Table In HTML:-

1. it is a collection of row and columns.
2. To create Table in html we use <table></table> tags.
3. Here we are creating table row by row. To create table row by row we use <tr></tr> tag.
4. <tr></tr> Tag we have to write within table tag.
5. To create cells html provides 2 tags.
   1.
    <Th></Th> Tag:- It is used to create table Heading Cells.
   2.  <Td></Td> Tag:- It is used to create Table Data Cells.
6. To provide title or caption to the table we use <caption></caption> Tag.
7. Caption tag we have to write within table tag.

# Cellspanning:-

Here we have to 2 ways to spans the cells.

1. colspan:- Colspan is an attribute used to span the cells on column basis.
2. rowspan:- rowspan is an attribute used to span the cells on row basis.

syntax:- We use these attribute inside cells.

   <td rowspan="3"  colspan="2"></td>
   <th rowspan="3" colspan="3"></th>

# Thead Tag:-
The Top most part of our table we have to write within <thead></thead> tag.

# Tfoot tag:- 
The bottom most part of our table (example:- conclusion or summary) we have to write within <tfoot></tfoot> tag.

# Tbody Tag:-
The remaining content of our table we have to write within <tbody></tbody> Tag.

# Note:- Thead, Tbody and Tfoot tag are highly recommended to used inside table for better explanation of code and crawler understanding purpose.

# Semantic Tag:-
Semantic Tags are self explantary tag.

Example:-
1. Header
2. Nav
3. Main
4. Section
5. Article.
6. Aside
7. Footer





# Form iun HTML:-

1. form are used to accept input from the user.
2. To create form in html we have <form></form> tag.
3. To create input field we use <input> tag. It is unpair tag.
4. Input tag we have to write within form tag.

#Attribute of input tag:-

1. Type Attribute:- Type attribute is used to specify which type of data we can accept in the that input field.

text
tel
email
password
file
data
time
datetime-local
color
range
search
url
submit
reset
number
radio
checkbox
month
week
image
button

2. Name Attribute:- name attribute is used to provide name to the input field.

3. Value Attribute:- value attribute is used to provide initial value to the input field.

4. disabled:- It will make the input field as disabled user can not access the input fiels.

5. Readonly:- It will make the input field as readonly user can not access the value but can access the input field.

6. Required:- It will make the input field as mandatory. if input field is empty form will not be submitted.

7. placeholder:- It is used to provide hint to the user.

8. autofocus:- Whenever page reload it will automatically focus an input field.

9. maxlength:- The maxlength attribute specifies the maximum number of characters allowed in the <input> element.

10. minlength:- The minlength attribute specifies the minimum number of character allowed in the <input> element.

11. autocomplete:- on/off

# Label tag:
Label tag is uesd to connect text with the input field.
The text we want to connect we have to write within label tag.
<label for="user-name">
  name
</label>  

Input tag we have to use id attribute and that id's value we have to pass to label's for attribute.
<input type="text" id="user-name">

whenever use click on that text respective input field will be focused.

# fieldset:-
fieldset tag is used to group form and it will create one box around all the elements.
Fieldset tag we have to write within form tag.

# Legend tag:- 
To provide title or caption to the form we use legend tag.
Legend tag we have to write within fieldset tag.

#Select tag:-
1. Select tag is used to access to create dropdown list.
2. Here we are providing multiple options to the user from these option user can select only one value.
3. To create option inside dropdown list we use option tag.
4. syntax:- 

      <select name="">
            <option value=""></option>
            <option value=""></option>
            <option value=""></option>
            <option value=""></option>
      </select> 

# Datalist:-
1. The datalist tag is introduced in HTML5
2. The Html datalist tag is used to provide an autocomplete feature on the form element.
3. Datalist tag is a container tag.
4. It is block level element.
5. It is used to provide a list of predefined options to the user
6. Datalist tag is used to create suggestion list or autocomplete list.
7. The <datalist> tag contains a set of <option>  tag that define the options in the list.
8. we are binding the suggestion list with the input field, for this we have to provide 'list' attribute in the input tag and 'id' attribute in the datalist tag, this same 'id'm we have to provide in the 'list' attribute of input tag.
9. whenever the user inputs in the input field related suggestions are displayed.
10. The advantage of using the datalist tag is that it allows user to enter values that are not present in the options list.

# Textarea:-
It is used to accept multiline input from the user.
  <textarea name=" " id="'></textarea>

  height:- rows="10"
  width:- cols="30"

# Difference between pair tag and Unpair Tag.
# Pair Tag:-
The pair tag we need to close are referred as pair tag.
      Eg:- <div></div>, <header></header>

# Unpair tag:-
The tag we need not to close are referred as Unpair tag.
    Eg:- <br>, <link>, <hr>, <image>, <source>

# Difference between Inline and Block level Element.

# Inline Level Element:- 
  i) it occupy space required by content.
  ii) We can not set height and width.
  iii) Example:- <br>, <hr>, <img>, <iframe>, <a>, <video>

# Block Level Element:- 
  i) It always take full width of its parent container.
  ii) We can set height and width.
  iii) Example:- <div>, <header>, <footer>, <section>, <article>, <aside>, <nav>, <main>, <body>, <fieldset>

# Difference between ID and Class Attribute.

# ID(#):-
  i) It is used to target element uniquely.
  ii) Multiple element can not have the same id.
  iii) One element can have only one id's value.
  iv) To target on element using id we use #.

# Class(.):-  
  i) It is used to target multiple element at a time.
  ii) multiple elements can have same class.
  iii) one element can have multiple class value.
  iv) To target an element using class in css we use .(dot).

# Div:- 
It is used to create block level container.

# Span:- 
It is used to create Inline level container.

# Element:- It is the combination of opening tag and content with closing tag.
     Example:- <p>Hello<p>




