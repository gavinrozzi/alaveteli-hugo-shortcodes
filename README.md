# Alaveteli Hugo Shortcodes

These shortcodes implement the [Alaveteli JSON API](http://alaveteli.org/docs/developers/api/) as shortcodes for the Hugo static site generator's [Data-Driven Content](https://gohugo.io/templates/data-templates/#data-driven-content) feature.

These shortcodes allow you to display data about public records requests from an Alaveteli instance and display them on a static site powered by Hugo. These shortcodes can be customized for other instances and currently support request statistics and recent requests.

## Using these shortcodes
To make use of these shortcodes on your own site, replace **example.com** in the HTML files with the domain of your Alaveteli instance.

For an example of these shortcodes in action on the developer's personal website, see [here](https://www.gavinrozzi.com/#opra) and also [here](https://www.gavinrozzi.com/project/opramachine/). The [OPRAmachine blog](https://blog.opramachine.com) also uses one of the shortcodes on its homepage. The example is based off of the **opramachine** branch of this repository.

One caveat to keep in mind is that even though the data is pulled directly from the API and not a static JSON file, the latest data is only loaded at build time due to the nature of static site generators.
