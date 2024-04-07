"Proyecto Edén - Tres Esferas" translates as "Project Eden - Three Spheres".

Eden stands for a good place, a human society living in harmony with one another and with the natural environment, where wild life and landscape have been kept and preserved, with no conflict with human affairs.

The Three Spheres are the three fields of concern that Westerners would presumably view reality through. These are:
- Nature
- Society
- Mind or Spirit

No doubt the Left is currently concerned with the Environment and Human Well Being, which fall within my first two spheres, and the Right also addresses issues with Nature and Society. Nevertheless, we often think that there is another dimension to our problems and that they should be approached from a mental or spiritual perspective. This doesn't exactly mean that we ought to become believers. Of course, all spiritual and "mental" traditions are welcome, though I am especially keen on Tibetan traditions. The point is, we must not force our views on others, just point to their existence as alternatives and made them available to others.

I would like to share this project and invite others to contribute to it through writing their own versions and commentaries as HTML pages that are linked to from withing this site and that link to other contributed pages, as a *graph* as opposed to a chain or sequence of texts (such as a novel) or a hierarchy of texts (such as a textbook).

GitHub has kindly allowed me to run a website as a subdomain at [proyecto-eden-3-esferas](https://proyecto-eden-3-esferas.github.io).

I intend to add some tools for writing and generally for communicating. Some of them have already been crafted, so all I can do is point to them and document them. I am in the course of developing other communication tools, too. Most of what I will be contributing will consist of templates (files with gaps to fill in in order to achieve something) and recipes, not much innovation as such in that.

For instance, I would like to provide some basic template of an HTML page so that others might fill it in and contribute to my project.

Below is one instance of a template. The contributer should copy the code below into a file named WHATEVER.html, replace the upper case prompts with their own content, and send it to me through some channel (only email for the time being):
```
<!DOCTYPE html>
  <html>
  <head>
    <title>TITLE_ON_BROWSER_WINDOW</title>
    <link rel=stylesheet href="MY_STYLESHEET.css" type="text/css" media=screen>
  </head>
  <body>
    <header>TITLE (NOT ESSENTIAL)</header>
    <nav>
      <p><a                    href="ANOTHER_PAGE.html">ANOTHER_PAGE</a></p>
      <p><a rel="RELATIONSHIP" href="ANOTHER_PAGE.html">LINK_TEXT</a></p>
      <p><a rel="alternate"    href="VERSION.html">ANOTHER VERSION</a></p>
      <hr/>
      <p><a            href="A_PAGE.html"       >LINK_TEXT</a></p>
      <p><a            href="ANOTHER_PAGE.html" >LINK_TEXT</a></p>
      <p><a rel="prev" href="PREVIOUS_PAGE.html">LINK_TEXT</a></p>
      <p><a rel="next" href="NEXT_PAGE.html"    >LINK_TEXT</a></p>
    </nav>
    <main>CONTENT AS <p>PARAGRAPH</p>'s, <table>TABLE</table>'s ETC</main>
    <footer>AUTHOR, REMARKS ETC</footer>
  </body>
</html>
```
Finally, some of the tasks that I wish to complete in English:
- [ ] A c++ geometry library, actually an extension to Boost.Geometry, to produce pictures in SVG, (Embedded) PostScript, and other vector formats
- [x] XSLT code to convert my DocBook files into HTML. (Stylesheets for this and other transformations are to be found at [https://github.com/proyecto-eden-3-esferas/XSLT](https://github.com/proyecto-eden-3-esferas/XSLT))
- [ ] A repository of worthy texts to be quoted
- [x] Documetation of my way and understanding of writing a book
