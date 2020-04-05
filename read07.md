Roy Fielding : he was the first one who write the first web server  
that sent documents across the Interne>
the http tells the browser what protocol to use. That stuff you type in there is one of the most important breakthroughs in the history of computing.

The whole world wide web is built on an architectural style called “REST”. REST provides a definition of a “resource”, which is what those things point to.
## what is a web page ?
A web page is a “representation” of a resource. Resources are just concepts. URLs--those things that you type into the browser.
## what is the URL?
 URLs tell the browser that there's a concept somewhere. A browser can then go ask for a specific representation of the concept. Specifically, the browser asks for the web page representation of the concept.

“Web Services” or "APIs". It means the concept is that machines could use the web just like people do.

##  how do the machines tell each other where things are?
he URL, If everything that machines need to talk about has a corresponding URL, you've created the machine equivalent of a noun.
Machines don't have a universal noun - that's why they suck. Every programming language, database, or other kind of system has a different way of talking about nouns. That's why the URL is so important. 
 ## IS get important ?
  It is. Especially when you're using a web browser because browsers pretty much just GET stuff. They don't do a lot of other types of interaction with resources. This is a problem because it has led many people to assume that HTTP is just for GETing. But HTTP is actually a general purpose protocol for applying verbs to nouns.
