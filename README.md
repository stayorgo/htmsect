# htmsect

htmsect is an html parser, with tools and ultilities to analyze html.
This html parser is available for golang, delphi, fpc, and in the future C language.  

It is based on fasthtmlparser, which is a delphi html parser that is fast, simple, and elegant.

The parser first splits the html into tag and text sections that you can analyze further.
Whenever a text section is found or a tag, an event (callback) occurs. In this function callback
or event you can analyze the name/value pairs in the tag or analyze the text. Many functions
are provided for analyzing html tags and syntax.

This parser is extremely simple and elegant since it treats html as a flat file and does 
not force you to parse html into a hiearchy structure or tree.
