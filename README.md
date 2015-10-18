# htmutils

htmutils is an html parser, with tools and ultilities to analyze html.
This html parser is available for golang, delphi, fpc, and in the future C language.  

It is based on fasthtmlparser, which is a delphi html parser that is fast, simple, and elegant.

The parser first splits the html into tag and text sections that you can analyze further.
Whenever a text section or tag is found, an event (callback) occurs. In the callback function
or event you can analyze the name/value pairs in the tag or analyze the text. Many functions
are provided for analyzing html tags, name value pairs, and other html syntax.

This parser is extremely simple and elegant since it treats html as a flat file and does 
not force you to parse html into a hiearchy structure or tree. Great for finding needles
in haystack (data mining, scraping, extracting information from the internet)
