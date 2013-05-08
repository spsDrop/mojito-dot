mojito-dot
==========

Adds a doT templates as a view engine for mojito.

Big props to olado for making the simplest fastest JS template engine known to MAN!
http://olado.github.io/doT/index.html

Simply name your views with the doT handler, like so.

index.doT.html

And use the doT syntax inside.

Partials are also supported


partials/snippet.doT.html

<b> I'm a partial </b>


index.doT.html

{{#def.snippet}}
