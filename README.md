This is a modified version of the [wikipedia_search_provider GNOME extension](https://extensions.gnome.org/extension/512/wikipedia-search-provider/) to also include some more functionality from the search bar.

# Using

`w <search term>` will search wikipedia

`c <math>` will do the math typed in. eg. 2 + 2 will show 4. uses mathjs library

# Developing

refresh:

`alt` + `f2`

log:

`journalctl /usr/bin/gnome-shell -f -o cat`
