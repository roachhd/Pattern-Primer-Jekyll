# Jekyll version of Pattern-Primer by adactio

Forked from the [original Pattern-Primer for PHP by adactio (Jeremy Keith)](https://github.com/adactio/Pattern-Primer)

Inspired by [Ruby (Sinatra) version](https://github.com/micdijkstra/Pattern-Primer-Ruby)

## Pattern Primer

Create little snippets of markup and save them to the "patterns folder." The pattern primer will generate a list of all the patterns in that folder. You will see the pattern rendered as HTML. You will also get the source displayed in a textarea.

## Why a Jekyll fork?

Why not? I could not have built it in PHP myself, but I am working on Jekyll projects and wanted to easily use Jeremy's tool without anything but Jekyll dependencies. It can be run locally or [on a live server](http://patternprimer.oliverpattison.org/) with great ease.

## How to use it

1. If you haven't already, [install Jekyll](http://jekyllrb.com/).
2. Clone this repo.
3. Copy your CSS file to css/global.css (replacing adactio's stock CSS) *or* copy your own CSS to the css directory and direct a link in the HTML to that file.
4. Run the command `jekyll serve` and open <localhost:4000> in your browser.

## Other versions

- [PHP (original version)](https://github.com/adactio/Pattern-Primer)
- [Node.js](https://github.com/beardtwizzle/pattern-primer-on-node)
- [Ruby (Sinatra)](https://github.com/micdijkstra/Pattern-Primer-Ruby)

## This is what it looks like

<http://patternprimer.oliverpattison.org/>

Note: my version uses the standard styles written by adactio.

## Credits

The **original** [Pattern Primer is by adactio](https://github.com/adactio/Pattern-Primer) and should be used if you prefer PHP or aren't already using Jekyll. Many thanks to Jeremy for this great tool!