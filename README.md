# Jekyll version of Pattern-Primer by adactio

Forked from the [original Pattern-Primer for PHP by adactio (Jeremy Keith)](https://github.com/adactio/Pattern-Primer)

Inspired by [Ruby (Sinatra) version](https://github.com/micdijkstra/Pattern-Primer-Ruby)

## Pattern Primer

Create little snippets of markup and save them to the "patterns folder." The pattern primer will generate a list of all the patterns in that folder. You will see the pattern rendered as HTML. You will also get the source displayed in a textarea.

## Why a Jekyll fork?

Why not? I couldn't have built it in PHP myself (nor could I have built it myself at all), but I'm working in Jekyll projects and wanted to easily port it without anything but Jekyll dependencies.

## How to use it

1. If you haven't already, [install Jekyll](http://jekyllrb.com/).
2. Clone this repo.
3. Copy your CSS file to css/global.css (replacing adactio's stock CSS) *or* copy your own CSS to the css directory and direct a link in the HTML to that file.
4. Run the command `jekyll serve` and open <localhost:4000> in your browser.

## Other versions

- [PHP (original version)](https://github.com/adactio/Pattern-Primer)
- [Node.js](https://github.com/beardtwizzle/pattern-primer-on-node)
- [Ruby (Sinatra)](https://github.com/micdijkstra/Pattern-Primer-Ruby)