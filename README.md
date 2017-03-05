Connectors
==========

Connectors provides an animated visualization of the connections between people you know and where they hang out online. Alternatively, you can connect any arbitrary nodes.

Screenshot
----------

![Connectors screenshot](connectors.png?raw=true)

Demo
----

https://pdurbin.github.io/connectors/

Installation and configuration
------------------------------

First, download the code in this repo. Then, put all your people and hangouts in `nodes.tsv`. Finally, link people to each hangout in `links.tsv`. Optionally, you can edit `index.html` to your liking.

To see the visualization you'll need to put `index.html`, `nodes.tsv`, and `links.tsv` on a web server. You can run one locally with `python -m SimpleHTTPServer` which should serve the three files at <http://localhost:8000>.

Acknowledgements
----------------

Connectors uses D3's [Force Layout][] in a configuration inspired by http://bl.ocks.org/ccmcc/5182685 and its name comes from The Tipping Point by Malcolm Gladwell.

[Force Layout]: https://github.com/d3/d3-3.x-api-reference/blob/master/Force-Layout.md
