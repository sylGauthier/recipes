# Suckless recipes.

This is a hard fork from Luke Smith's [based.cooking](https://based.cooking)
after much discontent with the writing quality, review process, and overall
"personal blog" feel of many recipes.

All recipes here have been rewritten to comply with a much stricter and rigorous
style. No personal stories, no donation links, the authors are still credited by
their names and websites but that's it.

The website building tools have been removed to separate code and data.

## General Rules

Recipes are not blog article, they should be impersonal. Nobody cares what's
your favorite spice to go with the dish, on what day of the week your mom would
cook this for you, etc. If you have something to add about how to cook the dish,
either put it directly into the `Directions` or add a `Note`, also in an
impersonal tone.

Write in proper English language, there are plenty of spell checkers out there.
The standard here is American English, so `flavor`, `customize`, `chili`, etc.
The plural of `chili` is `chilies`.

No images.

Don't name brands, especially for sauce, not all brands are available
everywhere, let alone under the same name.

Don't put any commercial links for ingredients or tools.

Your reader is probably smarter than you (think), don't explain trivial things.
Keep instructions short and readble. No wall of text.

**No donation link**.

See `example.md` for more detailed way of formatting recipes.

## Tags

You must add tags at the end of your recipe. The syntax is:
```
;tags: tag1 tag2 tag3
```

The tag line should be a single line, at the end of the markdown file, preceded
by a blank line.

Add between 1 and 4 tags, **prioritize existing tags**. As a general guideline,
add the country from which the recipe originates if the recipe is representative
of said country, using the adjective form (eg. *mexican*, *italian*, etc). Tag
the main ingredient if it's something slightly special.

List of special, categorical tags to use if relevant:
- `basic`: for basic recipes that aren't meant to be stand alone but are supposed
  to be incorporated in another recipe.
- `breakfast`
- `dessert`
- `drink`
- `quick`: for recipes that can be cooked in under ~20 minutes.
- `side`: side dishes such as mash, fries, etc.
- `snack`
- `spread`

## About this repository

It aims at providing the recipes and only the recipes. People can do whatever
they want with it, hosting a blog, converting them to pdf for printing, etc.

This README can present a list of repositories that offer ingenious way of
dealing with the recipes in the future, if there is enough interest for this to
ever happen.

Apart from the original based.cooking website, you can also use
[this tool](https://github.com/sylGauthier/cook) to convert/install/search/read
recipes as man pages.

It will be kept in sync (both ways) with based.cooking as much as possible.

## License

This repository and all its content is in the public domain.
By submitting text or images or anything else to this repository,
you waive any pretense of ownership to it,
although you are welcome and recommended to give yourself credit
at the bottom of a submitted page for you adding it
(including personal or donation links).
