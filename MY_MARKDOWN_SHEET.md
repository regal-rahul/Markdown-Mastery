# PARAGRAPH, TEXT FORMATTING

This is a paragraph.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.

This is _italic_

This is underscore _italic_

This is **bold**

This is ~~strike through~~

---

# HEADINGS

# Heading H1

This is a heading. Whenever you use '#' to make heading. github automatically put id on it.

## Heading H2

### Heading H3

#### Heading H4

##### Heading H5

###### Heading H6

---

# LINKS

This section includes diffrent kinds of links that can be used in [markdown](https://github.com/regal-rahul/Markdown-Mastery).

<https://github.com/regal-rahul>

[MY GITHUB ACCOUNT](https://github.com/regal-rahul)

[This Markdown Repository](https://github.com/regal-rahul/Markdown-Mastery "Go to this markdown repository on my github.")

Checkout my github account. [click here][1]

My github profile [here][2]. You can click [here][2] too, what are you waiting for click [here][2]

[1]: https://github.com/regal-rahul
[2]: https://github.com/regal-rahul

---

# IMAGES IN MARKDOWN

The format of image in markdown is `![]()`.

`![ Alt text ](image.jpg)`

![White Blossom](https://cdn.pixabay.com/photo/2015/04/19/08/32/marguerite-729510_960_720.jpg)

![Shepherd Dog](https://cdn.pixabay.com/photo/2019/07/23/13/51/shepherd-dog-4357790_960_720.jpg "Shepherd Dog")

![Child](https://cdn.pixabay.com/photo/2022/02/16/01/45/child-7015868_960_720.jpg "Happy Child")

## Reference to image link

![Daisy bee][bee]

[bee]: https://cdn.pixabay.com/photo/2022/06/29/08/26/daisy-7291228_960_720.jpg "Daisy bee"

## Link to larger version of image through thumbnail

Image link using markdown image link

[![Ice mountain](https://cdn.pixabay.com/photo/2022/04/29/17/48/lofoten-7164179_960_720.jpg)](https://cdn.pixabay.com/photo/2022/04/29/17/48/lofoten-7164179_960_720.jpg "Click Image for larger view")

---

Image link using img src into markdown, syntax `[<img src='example.com'>](large image link)`

[<img src="https://cdn.pixabay.com/photo/2022/04/29/17/48/lofoten-7164179_960_720.jpg">](https://cdn.pixabay.com/photo/2022/04/29/17/48/lofoten-7164179_960_720.jpg "Click for original image")

## Control width and height of image

<img src="https://cdn.pixabay.com/photo/2022/04/29/17/48/lofoten-7164179_960_720.jpg" width="200" height="150" alt="Mountain Image">

# LIST, BULLETS AND NESTING

## INGREDIENTS

- Water
- Sugar
- Milk
- Tea Leaves

## METHODS

Ordered list correct the numberig themselves if you type wrong order. Actually the numbering order doesnt matter. if you repeat same number it will list as incremental numbers.

1. Warm the water
2. Add sugar
3. Add milk
4. Add Sugar
5. Drink warm

---

Using same number i.e 1

1. Add sugar
1. Add Sugar
1. Add sugar
1. Drink warm

---

Using indentation in list

1. ONE
   - One Indent
   - One Indent
     - Indent inside indentation
1. TWO
1. THREE
   - Indentation
     - Further Indent
       - Again Indent
1. FOUR
1. FIVE

   - Indent diffrently

   This is inline

   ![Sheep](https://cdn.pixabay.com/photo/2022/05/08/20/39/sheep-7182968_960_720.jpg "Image in Inline indented list")

   ```js
   // Adding js code sample
   var x = 200;
   ```

# Line Breaks, Horizontal Rules and BlockQuotes

## LINE BREAKS

Markdown is cool.<br>
Line break is awesome.

Using line breaks

## HORIZONTAL RULES

Something

---

Another Thing

---

---

## BLOCK QUOTES

> This is not a quote but i would suggest to have more water and healthy food daily.
>
> — **Me**

> Sleep is important.

> Okay enough of blockquote.

# CODE BLOCK

Here is my code:

    var x = 100;
    const juice = 'mango';

Here is code specific code blocks:

```html
<li>Hello List</li>
<h1>Hello Heading</h1>
```

```js
var x = 100;
const pet = "dog";
```

```php
$age = 23;
$name = "dullu";
echo strtoupper($name);
```

```
var x = 100;
const pet = "cat";
```

Hey did you tried `var name = 'dullu'`?

Showing diffrence using -, + in code.

```diff
var x = 100;
- var y = 200;
+ var y = 100;
```
