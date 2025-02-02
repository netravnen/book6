## Markdown Usage

The basics of using the GitHub dialect of markdown are [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). As a general rule, please use the simpler constructs and avoid fancy formatting.

And don't forget, a separate .md file for each new section in any chapter of the book.

Diagrams can be ASCII art when applicable, e.g.:
~~~
   +-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+
   |Version| Traffic Class |           Flow Label                  |
   +-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+
   |         Payload Length        |  Next Header  |   Hop Limit   |
   +-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+
   |                              etc.                             |
~~~

The [*mermaid* tool](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams) can be used for flow charts and state diagrams, e.g.:

~~~
```mermaid
flowchart LR
    S[Start here] --> E[End here]
```
~~~

```mermaid
flowchart LR
    S[Start here] --> E[End here]
```

Other types of diagrams could be included using SVG generated by a separate drawing tool such as *dia*, with the SVG file also stored here on GitHub, e.g.:

~~~
<img src="./diag.svg">
~~~
<img src="./diag.svg">


<!-- Link lines generated automatically; do not delete -->
### [<ins>Previous</ins>](Section%20Template.md) [<ins>Next</ins>](Last%20Section.md) [<ins>Chapter Contents</ins>](99.%20Chapter%20Template.md)