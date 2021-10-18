<p align="center"> 
<a href="https://github.com/milaan9"><img src="https://img.shields.io/static/v1?logo=github&label=maintainer&message=milaan9&color=ff3300" alt="Last Commit"/></a> 
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmilaan9%2F/tree/main/markdown&count_bg=%231DC92C&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=views&edge_flat=false"/></a>
</p> 

# Getting started with Markdown

- Markdown - you can mark up titles, lists, tables, etc., in a much cleaner, readable and accurate way if you do it with HTML.

=============================


- [Getting started with Markdown](#getting-started-with-markdown)
- [Titles](#titles)
- [Paragraph](#paragraph)
- [List](#list)
	- [List CheckBox](#list-checkbox)
- [Link](#link)
	- [Anchor links](#anchor-links)
- [Blockquote](#blockquote)
- [Image | GIF](#image--gif)
- [Style Text](#style-text)
	- [Italic](#italic)
	- [Bold](#bold)
	- [Strikethrough](#strikethrough)
- [Code](#code)
- [Email](#email)
- [Table](#table)
	- [Table Align](#table-align)
    	- [Align Center](#align-center)
    	- [Align Left](#align-left)
    	- [Align Right](#align-right)
- [Escape Characters](#escape-characters)
- [Emoji](#emoji)
- [Shields Badges](#Shields-Badges)
- [Markdown Editor](#markdown-editor)
- [Some links for more in depth learning](#some-links-for-more-in-depth-learning)

----------------------------------

# Titles 

# Heading  1
## Heading  2
### Heading  3
#### Heading  4
##### Heading  5
###### Heading  6

    # Heading  1
    ## Heading  2
    ### Heading  3    
    #### Heading  4
    ##### Heading  5
    ###### Heading  6    


# Style Text

### Italic

*The greatest glory in living lies not in never falling, but in rising every time we fall.*

     *The greatest glory in living lies not in never falling, but in rising every time we fall.*

### Bold
**The way to get started is to quit talking and begin doing.**

    **The way to get started is to quit talking and begin doing.**
    
### Strikethrough
~~strikethrough text~~

    ~~strikethrough text~~
    
### keyboard input

<kbd>ALT + F4</kbd> 
```
<kbd>ALT + F4</kbd> 
```

### subscripted
normal text <sub>subscripted</sub> normal text
```
normal text <sub>subscripted</sub> normal text
```

### superscripted
normal text <sup>superscripted</sup> normal text
```
normal text <sup>superscripted</sup> normal text
```

# Paragraph
Successful people do what they like to do also they do what they feel correct for their business. If you look in the dictionary for the meaning of the word success then you will find that it means the achievement of one's goal or aim. So, basically, anyone can achieve success by *simply achieving their aim or goal*.

People experience success because they've achieved a level of natural self-confidence that allows them to take meaningful action. They've achieved a level of natural self-confidence that allows them to trust their behavior, rather than focusing on the outcome of that behavior.

    Successful people do what they like to do also they do what they feel correct for their business. If you look in the dictionary for the meaning of the word success then you will find that it means the achievement of one's goal or aim. 
    
    People experience success because they've achieved a level of natural self-confidence that allows them to take meaningful action.

# List 
1. First ordered list item
2. Another item
   * Unordered sub-list. 
4. Actual numbers don't matter, just that it's a number
   1. Ordered sub-list
5. And another item.  

       1. First ordered list item
       2. Another item
         * Unordered sub-list. 
       1. Actual numbers don't matter, just that it's a number
         1. Ordered sub-list
       4. And another item.  

   Some text that should be aligned with the above item.
   
       Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses

      * Unordered list can use asterisks
      - Or minuses
      + Or pluses

1. Today's
2. date is:
    * Monday
    * 16th January 1991
         - hello! how are
         - how are you?
             - Hope doing well

          1. Today's
          2. date is:
              * Monday
              * 16th January 1991
                   - hello! how are
                   - how are you?
                       - Hope doing well


## List CheckBox

 - [ ] Item A
 - [x] Item B
 - [x] Item C
 
       - [ ] Item A
       - [x] Item B
       - [x] Item C


# Link
[I'm an inline-style link](https://www.github.com)

      [I'm an inline-style link](https://www.github.com)

[Metric](https://en.wikipedia.org/wiki/Metric_(mathematics))

      [Metric](https://en.wikipedia.org/wiki/Metric_(mathematics))
 
[Metric](https://en.wikipedia.org/wiki/Metric_%28mathematics%29)

      [Metric](https://en.wikipedia.org/wiki/Metric_%28mathematics%29)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

      [I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

      [You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

      Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

      URLs and URLs in angle brackets will automatically get turned into links. 
      http://www.example.com or <http://www.example.com> and sometimes 
      example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com


      [arbitrary case-insensitive reference text]: https://www.mozilla.org
      [1]: http://slashdot.org
      [link text itself]: http://www.reddit.com


# Blockquote

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.
> 	This line is also part of the same quote.
>> This line too.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

    >Blockquotes are very handy in email to emulate reply text.
    >This line is part of the same quote.
    	>This line is also part of the same quote.
    >>This line too.
    
    >Quote break.
    
    >This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

# Inline HTML - You can also use raw HTML in your Markdown, and it'll mostly work pretty well.

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>
  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

      <dl>
        <dt>Definition list</dt>
        <dd>Is something people use sometimes.</dd>
        <dt>Markdown in HTML</dt>
        <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
      </dl>

# Horizontal Rule

Three or more...

---

      ---

Hyphens

***

      ***

Asterisks

___

>      ___

Underscores

# Line Breaks

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

    Here's a line for us to start with.

    This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

    This line is also a separate paragraph, but...
    This line is only separated by a single newline, so it's a separate line in the *same paragraph*.


# Code

```java
public static void main(String[] args) {
	//TODO
}
```

      ```java
      public static void main(String[] args) {
      	//TODO
      }
      ```

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

      ```javascript
      var s = "JavaScript syntax highlighting";
      alert(s);
      ```
 
```python
s = "Python syntax highlighting"
print s
```

      ```python
      s = "Python syntax highlighting"
      print s
      ```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

      ```
      No language indicated, so no syntax highlighting. 
      But let's throw in a <b>tag</b>.
      ```


# Email
<milaanparmar9@gmail.com>

    <milaanparmar9@gmail.com>

# Table

|Column 1|Column 2|Column 3|
|---|---|---|
|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|
|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|

>\|Column 1|Column 2|Column 3|<br>
>\|---|---|---|<br>
>\|Row 1 Column1| Row 1 Column 2| Row 1 Column 3|<br>
>\|Row 2 Column1| Row 2 Column 2| Row 2 Column 3|<br>

Colons can be used to align columns.

| Tables        | Are           | Cool  |
|:------------- |:-------------:| ------:|
| col 3 is      | right-aligned | \$1900 |
| col 2 is      | centered      |   \$12 |
| col 1 is      | left-aligned  |    \$1 |

>\| Tables        | Are           | Cool  |<br>
>\|:------------- |:-------------:| ------:|<br>
>\| col 3 is      | right-aligned | \$1900 |<br>
>\| col 2 is      | centered      |   \$12 |<br>
>\| col 1 is      | left-aligned  |    \$1 |<br>

The outer pipes **`|`** are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

>\Markdown | Less | Pretty<br>
>\--- | --- | ---<br>
>\*Still* | `renders` | **nicely**<br>
>\1 | 2 | 3<br>


### Table - _rowspan_

<table>
  <tr>
    <th>column 1</th>
    <th>column 2</th>
    <th>column 3</th>
  </tr>
  <tr>
    <td>row 1 - column 1</td>
    <td>row 1 - column 2</td>
    <td rowspan="2" align="center">row 1 & 2 - column 3</td>
  </tr>
  <tr>
    <td>row 2 - column 1</td>
    <td>row 2 - column 2</td>
  </tr>
</table>

```html
<table>
  <tr>
    <th>column 1</th>
    <th>column 2</th>
    <th>column 3</th>
  </tr>
  <tr>
    <td>row 1 - column 1</td>
    <td>row 1 - column 2</td>
    <td rowspan="2" align="center">row 1 & 2 - column 3</td>
  </tr>
  <tr>
    <td>row 2 - column 1</td>
    <td>row 2 - column 2</td>
  </tr>
</table>
```

### Table - _colspan_
<table>
  <tr>
    <th>column 1</th>
    <th>column 2</th>
    <th>column 3</th>
  </tr>
  <tr>
    <td>row 1 - column 1</td>
    <td colspan="2" align="center">row 1 - column 2 & 3</td>
  </tr>
  <tr>
    <td>row 2 - column 1</td>
    <td>row 2 - column 2</td>
    <td>row 2 - column 3</td>
  </tr>
</table>

```html
<table>
  <tr>
    <th>column 1</th>
    <th>column 2</th>
    <th>column 3</th>
  </tr>
  <tr>
    <td>row 1 - column 1</td>
    <td colspan="2" align="center">row 1 - column 2 & 3</td>
  </tr>
  <tr>
    <td>row 2 - column 1</td>
    <td>row 2 - column 2</td>
    <td>row 2 - column 3</td>
  </tr>
</table>
```

# Image

![Title](https://media.giphy.com/media/XRB1uf2F9bGOA/giphy.gif "description")

***Image:*** *description*

    ![myImage](https://media.giphy.com/media/XRB1uf2F9bGOA/giphy.gif "description")
    
    ***Image:*** *description*
    
<img src="https://media.giphy.com/media/XRB1uf2F9bGOA/giphy.gif" width=200/>

>      <img src="https://media.giphy.com/media/XRB1uf2F9bGOA/giphy.gif" width=200/>

| <img src="https://media.giphy.com/media/XRB1uf2F9bGOA/giphy.gif" width="200"/> | 
|:--:| 
| **Hi-Five** |

      | <img src="https://media.giphy.com/media/XRB1uf2F9bGOA/giphy.gif" width="200"/> | 
      |:--:| 
      | **Hi-Five** |

| ![space-1.jpg](http://www.storywarren.com/wp-content/uploads/2016/09/space-1.jpg) | 
|:--:| 
| *Space* |

      | ![space-1.jpg](http://www.storywarren.com/wp-content/uploads/2016/09/space-1.jpg) | 
      |:--:| 
      | *Space* |

![Random Unsplash Image](https://source.unsplash.com/random)    

      ![Random Unsplash Image](https://source.unsplash.com/random) 
    
## Image Align

### Image Align - Middle _(default)_

Reading is important because *it develops your mind and gives you excessive knowledge and lessons of life*. <img src="right-arrow.svg" width="42" height="42"> It helps you understand the world around you better. It keeps your mind active and enhances your creative ability. Communication Skills: Reading improves your vocabulary and develops your communication skills.

```html
<img src="right-arrow.svg" width="42" height="42">
```

### Image Align - Left

The seven habits are *visualizing, activating schema, questioning, inferring, determining importance, monitoring for meaning and synthesizing*. <img src="left-arrow.svg" alt="left face" align="left" width="42" height="42"> Visualizing allows the student to form mental pictures about what they are reading to aid their comprehension of a text.

```html
<img src="left-arrow.svg" alt="left face" align="left" width="42" height="42"> 
```

### Image Align - Right

When you read, you exercise your comprehension abilities and your analytical abilities. It fires up your imagination and stimulates the memory centers of your mind. <img src="right-arrow.svg" alt="right" align="right" width="42" height="42"> It helps recall information as well as stabilize your emotions. The importance of a reading habit is that it *strengthens mental muscles*.

```html
<img src="right-arrow.svg" alt="right" align="right" width="42" height="42">
```

# Escape Characters

```
\   backslash
/   forwardslash
|   separator
`   backtick
*   asterisk
^   power
_   underscore
{}  curly braces
[]  square brackets
()  parentheses
#   hash mark
+   plus sign
-   minus sign (hyphen)
.   dot
!   exclamation mark
```

# Emoji

* [Emoji](emoji.md#emoji)
	* [People](emoji.md#people) - (:blush: ; :hushed: ; :shit:)
	* [Nature](emoji.md#nature) - (:sunny: ; :snowman: ; :dog:)
	* [Objects](emoji.md#objects) - (:file_folder: ; :computer: ; :bell:)
	* [Places](emoji.md#places) - (:rainbow: ; :warning: ; :statue_of_liberty:)
	* [Symbols](emoji.md#symbols) - (:cancer: ; :x: ; :shipit:)
* [Kaomoji](emoji.md#kaomoji)
* [Special-Symbols](emoji.md#special-symbols)

# YouTube Videos

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

    <a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
    " target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
    alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Example:

<a href="https://www.youtube.com/watch?v=w3jLJU7DT5E&ab_channel=GitHub" target="_blank"><img src="youtube.png" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Or, in pure Markdown, but losing the image sizing and border:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

    [![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

Example:

[![IMAGE ALT TEXT HERE](youtube.png)](https://www.youtube.com/watch?v=w3jLJU7DT5E&ab_channel=GitHub)

# TeX Mathematical Formulae

A full description of TeX math symbols is beyond the scope of this cheatsheet. Here's a [good reference](https://en.wikibooks.org/wiki/LaTeX/Mathematics), and you can try stuff out on [CodeCogs](https://www.codecogs.com/latex/eqneditor.php). You can also play with formulae in the Markdown Here options page.

Here are some examples to try out:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" title="\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" />

    <img src="https://latex.codecogs.com/svg.latex?\Large&space;x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" title="\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" />

![\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}](https://latex.codecogs.com/svg.latex?\Large&space;x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}) 

    ![\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}](https://latex.codecogs.com/svg.latex?\Large&space;x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}) 
    
![\Large x=a_0+\frac{1}{a_1+\frac{1}{a_2+\frac{1}{a_3+a_4}}}](https://latex.codecogs.com/svg.latex?\Large&space;x=a_0+\frac{1}{a_1+\frac{1}{a_2+\frac{1}{a_3+a_4}}})

    ![\Large x=a_0+\frac{1}{a_1+\frac{1}{a_2+\frac{1}{a_3+a_4}}}](https://latex.codecogs.com/svg.latex?\Large&space;x=a_0+\frac{1}{a_1+\frac{1}{a_2+\frac{1}{a_3+a_4}}})
    
![\Large \forall x \in X, \quad \exists y \leq \epsilon](https://latex.codecogs.com/svg.latex?\Large&space;\forall{x}\in{X},\quad\exists{y}\leq\epsilon)

    ![\Large \forall x \in X, \quad \exists y \leq \epsilon](https://latex.codecogs.com/svg.latex?\Large&space;\forall x \in X,\quad \exists y \leq \epsilon)


Here is a simple script to convert the equation into html: https://jsfiddle.net/8ndx694g/

Step 1: Paste LaTex Equation   

    x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}

Step 2: Click on "Econdode to github render URL"

    <img src="https://render.githubusercontent.com/render/math?math=x%20%3D%20a_0%20%2B%20%5Cfrac%7B1%7D%7Ba_1%20%2B%20%5Cfrac%7B1%7D%7Ba_2%20%2B%20%5Cfrac%7B1%7D%7Ba_3%20%2B%20a_4%7D%7D%7D">

Step 3: Copy and Paste genrated URL

<img src="https://render.githubusercontent.com/render/math?math=x%20%3D%20a_0%20%2B%20%5Cfrac%7B1%7D%7Ba_1%20%2B%20%5Cfrac%7B1%7D%7Ba_2%20%2B%20%5Cfrac%7B1%7D%7Ba_3%20%2B%20a_4%7D%7D%7D">

# Shields Badges

See more: [https://shields.io/](https://shields.io/)

[![GitHub forks](https://img.shields.io/github/forks/milaan9/01_Python_Introduction)](https://img.shields.io/github/forks/milaan9/01_Python_Introduction)
![Markdown](https://img.shields.io/badge/markdown-project-red)

# Markdown Editor

[StackEdit](https://stackedit.io) - _StackEdit’s Markdown syntax highlighting is unique. The refined text formatting of the editor helps you visualize the final rendering of your files._

# Some links for more in depth learning

:page_facing_up: [Wikipedia - Markdown](https://en.wikipedia.org/wiki/Markdown)

:page_facing_up: [Official](https://daringfireball.net/projects/markdown/)
