# Heading with one hash

## Heading with two hashes

### Heading with three hashes

#### Four hashes

##### Five hashes

###### Six hashes

####### Seven hashes

Normal text:

Normal text can use *stars* (`*text*`) and _underscores_ (`_text_`) and *_both_* (`*_text_*`), yet, both are rendered as italics.
With **double stars** (`**text**`), the text turns bold, with **_double stars and an underscore_** (`**_text_**`) it turns bold and italic.
Text between ~~two tildes~~ (`~~text~~`) is stroken through. This is text `enclosed in back-ticks` (`` `text` ``).

And then, there are also [links](https://raw.githubusercontent.com/ReneNyffenegger/about-README.md/master/README.md).
Normal urls (such as https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) are rendered as links as well.

    This seems to be like code.

    It needs at least four whitespaces
    at a line's beginning

A table. Note the rigth and left alignment (by means of the *colons*):

|number|english|german |
|-----:|:------|:------|
|     1|one    |eins   |
|     2|two    |two    |
|     3|three  |drei   |
|    10|ten    |zehn   |
|    20|twenty |zwanzig|
|   100|hundred|hundert|

# Links in Code

Links in *indented* code don't work:

     function FooBar(a, b) {
        return a + b;  // [github](www.github.com)
     }


They work with the `<pre>` tag, however:

<pre>
function FooBar(a, b) {
   return a + b;  // <a href='http://www.github.com'>github</a>
}
</pre>

# Lists

- First item of a list
- Second item of a list
  - first sub item of second item<br>
    additional text for first sub item of second item *Note the `<br>` here.*
  - second sub item of second item
    additional text for second sub item of second item *Note the lack of a `<br>` here.*
- third item
    

# Horizontal Lines

Three stars `***`, underscores `___` or hyphens `---` produce a

---

# Misc

<font style="color:red">Some red text (doesn't work)</font>

# Links

- [Markdown live demo](http://markdown-here.com/livedemo.html)
- [Adam Pritchard's markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
