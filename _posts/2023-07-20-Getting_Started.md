---
layout: page
cover: 'assets/images/golden.jpg'
navigation: True
title:  "Getting Started"
date:   2023-07-20 11:59:00 -0700
tags: test content
subclass: 'post tag-test tag-content'
logo: 'assets/images/logo.png'
author: david
categories: jekyll update
---
## Liturature & Reports

This is just an *ipsis verbis* copy of the first example running on the [Ghost Demo](http://demo.ghost.io). This shows how you can use html styling to achieve your hopes.

Below is just about everything you’ll need to style in the theme. Check the source code to see the many embedded elements within paragraphs.

---

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---

Lorem ipsum dolor sit amet, [test link](#) adipiscing elit. **This is strong.** Nullam dignissim convallis est. Quisque aliquam. *This is emphasized.* Donec faucibus. Nunc iaculis suscipit dui. 5^3^ = 125. Water is H~2~O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. ~~The New York Times~~ (That’s a citation). <ins>Underline.</ins> Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.

HTML and CSS are our tools. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.  Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus. To copy a file type `COPY <var>filename</var>`. <del>Dinner’s at 5:00.</del> <ins>Let’s make that 7.</ins> This <strike>text</strike> has been struck.

---

## Media

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore.

### Big Image

![Test Image](http://demo.ghost.io/content/images/2014/09/testimg1.jpeg)

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

### Small Image

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore.

![Small Test Image](http://demo.ghost.io/content/images/2014/09/testimg2.jpg)

Labore et dolore.

---

## List Types

### Definition List

Definition List Title
: This is a definition list division.

Definition
: An exact statement or description of the nature, scope, or meaning of something: *our definition of what constitutes poetry.*

### Ordered List

1. List Item 1
2. List Item 2
   1. Nested list item A
   2. Nested list item B
3. List Item 3

### Unordered List

- List Item 1
- List Item 2
  - Nested list item A
  - Nested list item B
- List Item 3

---

## Table

| Table Header 1 | Table Header 2 | Table Header 3 |
| -------------- | -------------- | -------------- |
| Division 1     | Division 2     | Division 3     |
| Division 1     | Division 2     | Division 3     |
| Division 1     | Division 2     | Division 3     |

---

## Preformatted Text

Typographically, preformatted text is not the same thing as code. Sometimes, a faithful execution of the text requires preformatted text that may not have anything to do with code. Most browsers use Courier and that’s a good default — with one slight adjustment, Courier 10 Pitch over regular Courier for Linux users.

### Code

Code can be presented inline, like `<?php bloginfo('stylesheet_url'); ?>`, or within a `<pre>` block. Because we have more specific typographic needs for code, we’ll specify Consolas and Monaco ahead of the browser-defined monospace font.

Code blocks can also be inserted with the highlight tag as below:

{% raw %}
{% highlight language-x %}

some code
{% endhighlight %}
{% endraw %}

More information about code highlighting in jekyll can be found [in Jekyll documentation](https://jekyllrb.com/docs/templates/#code-snippet-highlighting).

These area a couple of examples showing the resulting highlighted code:

{% highlight css %}
/* css code sample */
#container {
    float: left;
    margin: 0 -240px 0 0;
    width: 100%;
}
{% endhighlight %}

{% highlight javascript %}
// javascript code sample
$.ajax({
  type: 'POST',
  url: 'backend.php',
  data: "q="+myform.serialize(),
  success: function(data){
    // on success use return data here
  },
  error: function(xhr, type, exception) {
    // if ajax fails display error alert
    alert("ajax error response type "+type);
  }
});
{% endhighlight %}

Now you can also use [highlight.js](https://highlightjs.org/).
For more on how to use it and on the available styles check their [demo](https://highlightjs.org/static/demo/) and [documentation](http://highlightjs.readthedocs.org/en/latest/) pages.

// Swift code sample
import Foundation

@objc class Person: Entity {
var name: String!
var age: Int!

init(name: String, age: Int) {
/* /* ... */ */
}

// Return a descriptive string for this person
func description(offset: Int = 0) -> String {
return "(name) is (age + offset) years old"
}
}

---

## Blockquotes

Let’s keep it simple. Italics are good to help set it off from the body text. Be sure to style the citation.

> Good afternoon, gentlemen. I am a HAL 9000 computer. I became operational at the H.A.L. plant in Urbana, Illinois on the 12th of January 1992. My instructor was Mr. Langley, and he taught me to sing a song. If you’d like to hear it I can sing it for you. — [HAL 9000](http://en.wikipedia.org/wiki/HAL_9000)

And here’s a bit of trailing text.

---

## Text-level semantics

The [a element](#) example  
The <abbr>abbr element</abbr> and <abbr title="Title text">abbr element with title</abbr> examples  
The **b element** example  
The *cite element* example  
The `code element` example  
The <del>del element</del> example  
The <dfn>dfn element</dfn> and <dfn title="Title text">dfn element with


