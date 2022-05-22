<head>
    <title>HTML and CSS</title>
    <h1> HTML and CSS</h1>
</head>

<a href ="https://www.w3schools.com/colors/colors_picker.asp">HTML COLOR PICKER </a>

<br/>

**<h3>Basic Structure:</h3>**

- `<html>` Shows that what inside is HTML code `</html>`
- `<title>` Shows the title of the webpage `</title>`
- `<body>`Anything in here will be displayed on Webpage`</body>`

<br/>

**<h3>Text</h3>**

| Description |     | Tags                     |
| ----------- | --- | ------------------------ |
| Headers     |     | `<h1>` to `<h6>`         |
| Paragraphs  |     | `<p>Makes paragraph</p>` |
| Bold        |     | `<b></b> `               |
| Italic      |     | `<i></i>`                |
| Address     |     | `<address></address>`    |
| Superscript |     | `<sup></sup>`            |
| Subscript   |     | `<sub> </sub>`           |

<br/>

**<h3>Empty Elements:</h3>**

| Description      |     | Tags                              |
| ---------------- | --- | --------------------------------- |
| Line Break       |     | `<br />`                          |
| Hori Rule        |     | `<hr />`                          |
| Quote            |     | `<q></q>`                         |
| Indented Quote   |     | `<blockquote></blockquote>`       |
| Abbreviations    |     | `<abbr title=”...”> </abbr>`      |
| Acroynm          |     | `<acronym title=”...”></acronym>` |
| Referencing      |     | `<cite title = “...”></cite>`     |
| Definition       |     | `<dfn></dfn>`                     |
| Insert/Underline |     | `<ins></ins>`                     |
| Strikethrough    |     | `<s></s>`                         |
| Delete through   |     | `<del></del>`                     |

<br/>

<h3><b>Lists:</b></h3>

Three types – Ordered lists, Unordered lists and Definition lists

| Description                            |     | Tags   |
| -------------------------------------- | --- | ------ |
| Unordered List                         |     | `<ul>` |
| Ordered List                           |     | `<ol>` |
| List Item                              |     | `<li>` |
| Description List                       |     | `<dl>` |
| Defines a Term in Description List     |     | `<dt>` |
| Describes the Term in Description List |     | `<dt>` |

Eg:

```html
<dl>
  <dt>terms</dt>
  <dd>definition</dd>
</dl>
```

<br/>

<h3><b>HTTP Methods</b></h3>

- GET
- POST
- PUT
- HEAD
- DELETE
- PATCH
- OPTIONS
- CONNECT
- TRACE

<br/>

Links:
Links are created by <a href = “url”>link text</a> element
Uses href attribute
Links absolute site= <a href = “www.s.com”>link text</a>
Links relative site = <a href = “home.html”>link text</a>
Homepage is called index.html
Same Folder = <a href = “next.hmtl”></a>
Child Folder = <a href = “doc/next.html”></a>
Grandchild Folder = <a href = ”doc/work/nextnext.html”></a>
Parent Folder = <a href = “../index.html”></a>
Grandparent Folder = <a href = “../../index.html”></a>
Email links(add mailto):
mailto = <a href = “mailto: email”></a>
Opening new window: (add target)
Target = <a href = “URL” target =”_blank”></a> (must be \_blank for target value)
Link to a part on webpage: (use id attribute)

`<h1 id= ”top”></h1>` sets point to jump
`<a href = “#top”></a> <a>` jumps you
Or
`<a href = “URL/#top”></a> <a>` jumps you

Images: (empty elements)
You must always specify a src attribute to indicate the source of an image and an alt attribute to describe the content of an image.
Adding Images = <img src = “desitination/URL” alt = “def if picture not shown” title = “more info” />
Attributes:
<img src = ”” />
<img alt = ”” />
<img tilte = ”” />
<img width = ”” />
<img height = ”” />
<img align = ”” /> (right/left/top/middle/bottom)
Three Steps of Images:
Right format
Right Size
Use right resolution

Tables:
Used to create table `<table>....</table>`
Row Maker: <tr> </tr>
Cell: <td> # or “”</td>
Spanning cells: <td colspan = “#”> “” <td>

<td rowspan = “#”> “” <td>
Empty Cell: <td></td>
Header: <th scope = “col/row”> “”</th>
Long Tables (Should sit in)
Headings: <thead></thead>
Body: <tbody></tbody>
Footer: <tfoot></tfoot>

Forms:
Form Structure:
Form: <form></form> - Carries the action, method and id attribute
Action: <form action = “URL”>
Method: <form action = “URL” method =””>

<br/>

### Input tag

- `<input attri's...>`

| Types Attributes |     |        |     |                                                                 |
| ---------------- | --- | ------ | --- | --------------------------------------------------------------- |
| button           |     | time   |     | date                                                            |
| datetime-local   |     | week   |     | email                                                           |
| file             |     | hidden |     | image                                                           |
| month            |     | number |     | password                                                        |
| radio            |     | range  |     | reset                                                           |
| search           |     | submit |     | tel                                                             |
| text             |     | url    |     |                                                                 |
|                  |     |        |     | [More Attributes](https://www.w3schools.com/tags/tag_input.asp) |

<br/>

### Adding Text:

Text Area(multi-line)(doesn’t need `<p>`)
`<textarea name = “comments” cols =”20” rows = “4”> Enter thoughts <textarea>`
Hidden Text:
`<input type="hidden" name="bookmark" value="lyrics" />`

Making Choices:
Radio Buttons(select one)
`<p><input type="radio" name = "genre" value = "pop" checked ="checked"> Pop </p>`
Checkboxes(select one or more)
`<p> <input type="checkbox" name="site" value="itunes" checked="checked" /> Itunes </p>`
Drop-down Boxes
Select and Options
Mupltiple lets you select more than one
<select name="devices" size="3" multiple="multiple">

<option value = "phone"> Phone </option>
<option value = "radio"> Radio </option>
<option value = "computer"> Computer </option>
<option value = "pad"> Pad </option>
</select>

### Uploading Files:

File upload
`<input type="file" name="user-song" />`

• Submitting Forms:
Submit button
`<input type="submit" name ="upload" value="Upload" />`
• Value give the button the name
Image buttons
`<input type="image" src = "File Destination" width="100" height="20" />`

• Custom Buttons: (text with pic button)
`<button><img src="images/add.gif" alt="add" width="10" height="10" /> Add </button>`

- Labeling
  - The “for” in label allow you to click on the text and and it will also select. Works with “id” and “for” values

`<label> Age: <input type=”text” name=”age” /> </label>`
`<input id=”pop” type="radio" name = "genre" value = "p" checked ="checked">` `<label for=”pop”>POP</label>`

- Grouping Elements:
  - `<fieldset>....</fieldset>` - This groups them
- Header:
  - `<legend> “” </legend>` - this names the grouping
- Form Validation:
  - `<input type = "password" name = "password" size = "15" maxlength = "30" required="required"/>`
- Date Input:
  - `<input type="date" name="todaydate"/>` - will make date box
- URL Input:
  - `<input type="url" name="urllink"/>` - will want a url
- Email Input:
  - `<input type="email" name="emailinput"/>` - will want a email
- Search Input:
  - `<input type="search" name="emailinput" placeholder="search"/>`
    <p>Placeholder is for what in the text box</p>

Extra markup:

Doctypes  
• Tell us the type of version of HTML
• <!DOCTYPE html>
Comments
• <!—comment 
ID Attribute
• Every Element can carry ID, its a unique identity elements
• <p id=”...”> ....</p>
Class attribute:
• Can be on every element used to identify several elements as different
• <p class=”...”> ....</p>
Grouping text and elements:
• Can group sets of elements together block wsie
• <div> elements </div> - put it elements inside to be part of block
Grouping text and elements inline:
• Groups inline text or elements
• <span> TEXT </span> - put it already elements
Iframes:
• A window in your page and the window is another page
• <iframe... ></iframe>
o Width= “###”
o Height= “###”
o Marginheight =”0”
o Marginwidth =”0”
o Src =”url”
o Scrolling=”yes/no” – hide or show scroller
o Frameborder = “0/1” – hide or show border
o Seamless
Information about page
• Meta live inside <head> element and contains information
• <meta ... />
o Name=”description” content =“page’s description”
 – used for search engine to understand page
o Name=”keywords” content =”list, like, this” – list of keywords user might search
o Name=”robots” content=”noindex/nofollow”
 Indicates if search engines add this page to results
 Noindex – if it mustn’t be added
 Nofollow – can be added but not the links on page
o http-equiv=”author” content =”” – author of page
o http-equiv=”pragma” content =”no-cache” – no chaching the page
o http-equiv=”expires” content =”Fri, 04 Apr 2014 23:59:59 GMT”  
 -when it is removed from cache (date must be in that format)
Escape Characters
• Use these if you want them on page
FLASH AND VIDEO COME BACK TO THAT NONSENSE!!!

CSS
Intro to CSS:

CSS allows you to create rules that control the way each box is presented and contents inside of box.
CSS rules contains two parts selector and declaration
Selectors indicate which elements it applies – p{....declarations ; declaration}
Declarations how elements are styled - font-family: Arial (two parts - property: value)

<br/>

Using external CSS file

- Use <link ..... /> with href, type and rel
  - Href = “cssfile.css”
  - Type = ”text/css”
  - Rel = “stylesheet”

Using internal CSS:

- Use `<style ...>` CSS code{} `</style>` - normally in Html `<head>` element
- type = ”text/css”

### CSS Selectors:

• Universal Selector - _{} – all <> elements
• Type selector – h1, p ,h2 {} – all `<h1>, <h2>, <p>`
• Class selector -.note {} – any element that has class=”note”
o P.note {} – any `<p>` elements that has class=”note”
• ID selector – #introduction {} - elements whose ID value is introduction
• Child selector – li>a {} – any `<a>` elements in `<li>`
• Descendant selector – p a {} – any `<a>` elemts that sit inside `<p>`
• Adjacent sibling – h1+p {} – first `<p>` element after `<h1>`
• General sibling – h1~p {} - any `<p>` elements after `<h1>`
Attribute Selectors:
• Existence – p[class] {} – targets any <p> element with attribute called class
• Equality – p[class=”word”] {} – targets any <p> element with attribute class = “word”
• Space – p[class~=”dog”] {} – targets <p> with attribute class and list of words with one being dog
• Prefix – p[attr^=”d”] {} – targets <p> with attribute’s value that begins with “d”
• Suffix – p[attr$=”g”] {} – targets <p>with attribute’s value ending with “g”
• Substring – p[attr_=”do”] {} – targets <p> elements with attribute containing “do”

CSS Rules Cascade:
• Last Rule
o Last selector is done
• Specificity
o One that is more specific is done (h1{} over \*{})
• Important
o Add “!important” to any value to so more important than other rules
Inheritance:
What you give the tops most element changes all the children

Colour:

Can specify them in 3 ways:
• RGB - colour : rgb(100,100,9);
o RGBa – colour: rgba(100,100,100,0.5) – last parameter is alpha/opacity
• Hex codes - colour : #ee3e80;
• Names - colour : DarkCyan;  
Background:
• Background-color: RGB/RGBa/Hex/Names ;
o Opacity: 0.5 ; - must come after one of the above and is 50%
Hue, Saturation and Lightness
Background-colour : hsl(0, 100%, 100%, 0.5)
• Hue is 0 to 360
• Saturation is percentage
• Lightness is percentage with 0% being white
• Alpha is opacity

Image
Imagine Opacity/transparency: img{opacity : ...} 1= full, 0.5 – half

Text

There are different font families and styles. You can have sets of fonts in order of if they on pc.
• Selecting font
o Body { font-family: Georgia, times, serif;} – on of them will be used starting with Georgia
• Size of type
o Body {font-size: 12px/200%/1.5em;} – any type
 Xx-Small, medium, xx-large, smaller, larger
• Font face
o @font-face{ font-family: ‘Font’;
src: url(‘font path’) , format (‘type’);}
o As
o Fortmat (‘...’) – eot/woff/tff/svg
o H1 {font-family: Fontdownload, Georgia ;} –can use it
• Bold
o Body{font-weight: bold/normal;}
 Bolder, lighter, 100,200 etc
• Italic
o Body{font-style: italic/normal/oblique;}
• Case:
o Body{text-transform: uppercase/lowercase/capitalize;}
• Underline or strike
o Body{text-decoration: none/underline/overline/line-through/blink;}
• Overflow
o Div.a{text-overflow: clip/ellipsis} – when text has border and has overflow added this added a clip or ellipsis without overflow:hidden;

• Leading
o Body{line-height: 1.5em;}
• Letter and word spacing
o H1{letter-spacing: 0.2em;}
o H1{word-spacing: 1em;}
• Alignment
o P{text-align: left/right/center/justify;}
• Vertical alignment
o P{vertical-align: baseline/sub/super/top/text-top/middle/bottom/text-bottom;}
• Identing text
o H1{text-indent: 20px;} – minus is left and normal is right.
• Drop Shadow
o {text-shadow: 1px 1px 0px #hexcolour ;}
 1st value - how far left or right it should fall
 2nd value – how far top or bottom is should fall
 3rd value – specifies the blur(optional)
 4th value – color of drop shadow
• Pseudo-elements
o First-letter
 P:first-letter { ....}
o First line
 P.intro:first-line{.....}
o Styling Link
 - a:link {.....} – allows you to set styles to link not visited
 - a:visited{....} – allow you to set styles for links that have been clicked on.
 - input.submit:hover {...} – applied when user hovers over element
 - input.text:focus{...} – applied to element that had focus
 - input.submit:active{....} – applied when element is clicked

Boxes
• Box dimensions
o – div { height: 300px; width: 300px}
• Limiting dimensions
o Height/Width
 {min-height/width: #px ;} -smallest
 {max-height/width: #px ;}-highest
• Overflowing content
o {overflow: hidden;} – ifs contents is larger than box hide rest
o {overflow: scroll;} – if contents is larger add scrollbar
• Margin, border, padding, Content (in that order)
o Border
 Shorthand
• {border: width style color}
 Width (no %)
• {border-width: #px;} – all same border
• {border-width: #px #px #px #px;} – order of width top,right,bottom,left
o {border-top/right/bottom/left-width: #px;}
• {border-width: thin/medium/thick;}
 Border style
• {border-style: solid/dotted/dashed/double/groove/ridge/inset/outset/hidden;}
o {border-top/left/right/bottom-style: solid/...}
 Border color
• {border-color: Hex/RGB/Names;}
• {border-color: value value value value; } – clockwise

o Padding - {padding: #px/ #% ;}
 {padding: #px #px #px #px;}
 Or {padding-top/right/bottom/left: #px ;}
o Margin – {margin: #px/%/em ;}
 {margin: #px #px #px #px ;} – can be done with list also
 Or {margin-top/right/bottom/left;}
o Centering content
 {margin: #px auto #px auto;}
o Change inline/block
 Allows you to turn inline element into block-level
 {display: inline/block/inline-block/none ;} –none will no spaces left
o Hiding Boxes
 Allows you to hide boxes from user but leaves space
 {visibility: hidden/visible}
o Border images
 {border-image: url(””) # # # # stretch/repear/road;}

Lists, Tables and Forms:
• Bullet Point Styles
o – ul { list-style-type: ...;}
 - none
 - disc
 - circle
 - square
o – ol {list-style-tape: ....;}
 - decimal
 - decimal-leading-zero
 - lower-alpha / lower-roman
 - upper-alpha / upper-roman
• Images for Bullets
o – ul{list-style-image: url”..”;} – only ul with li
• Positioning he marker
o – ul{list-style-position: outside/inside;}
• List style shorthand
o – ul{list-style: inside circle ;}
• Table properties
o Width - table{ width: 600px;}
o Padding – th, td {padding: #px #px #px #px;}
o Text-transform – th(text-transfrom: uppercase;)
o Leter-spacing
o Font-size
o Border-top/bottom
o Text-align
o Background-color
o :hover

• Border on empty cells
o – table {empty-cells: show / hide / inherit ;}
• Gaps between cells
o – table{ border-spacing : #px #px} – space cells
o – table {border-collapse: collapse} - no spaces
o – table {border-collapse: serparate} – all cells are detached
• Styling inputs
o - input#email { background-image: url(“...”);} – add image to input background
• Cursor Styles
o - a {cursor: ... ;}
 Auto
 Crosshair
 Default
 Pointer
 Move
 Text
 Wait
 Help
 url(“...”);

Layout
• normal flow – doesn’t have to be added
o – p{position: static;}
• Relative flow – moves elements relative to normal
o – p{position: relative;} – to move it use bottom/top/left/right
• Absolute positioning - no longer normal and doesn’t affect
o – h1 {position: absolute;} – move it anywhere
• Fixed positioning – stay in same place even when scrolling
o – h1 {position: fixed;} –set it with properties
• Overlapping elements – doesn’t matter about positioning
o – h1 {z-index}
• Floating elements – allows you to place far left or right
o Can you floating elements to place elements side-by-side
o Blockquote{float: right;}
• Clearing floats
o Allows you to select if other floats can touch the float clear is in
o – p{clear: left/right/both/none;}
 None means it can touch both sides

## Extra

---

- Comments: /_ ....._/.
- Percent and EM are not Relative Measurements and the size of each doesn’t depend on its parents
- Pixels are not recommended units for specifying size
- Font-family attribute does not help ensure maximum compatibility between web browsers

- Bitmaps are img
- Image in pixel on Javascript is canvas
- XMl is svg
