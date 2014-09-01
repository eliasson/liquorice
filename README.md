# liquorice

Liquorice is a small black and white theme for [Hugo](https://github.com/spf13/hugo) (a fast and modern static website engine).


### Dependencies

Liquorice needs at least version 0.12 of Hugo, as it uses features such as partials.


### Shortcodes

Liquorice comes with these additional shortcodes:


#### gist

Include a Github gist using their JavaScript include.

    {{% gist e572b28c9a0eef0b2763 %}}

Where the first parameter is the gist id.


### Building

There is not much to build, but the theme CSS is minified using the node tool [clean-css](https://github.com/GoalSmashers/clean-css).

    cleancss -o static/css/liquorice.min.css static/css/liquorice.css

*Any change in styles needs to result in a minification!*


# License

Liquorice is released under the MIT license, see LICENSE for details.