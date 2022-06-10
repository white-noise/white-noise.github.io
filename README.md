# may: a smaller, sister site

## notes on style and todo
- Modifying theme to remove all reference to `minima`
- Date formatting
- Toggling pagination on and off per variables
- Additional post metadata for future reference (tags, etc.)
- New github account or otherwise
- See Jekyll cheat sheet [here](https://gist.github.com/JJediny/a466eed62cee30ad45e2)
- Succinct styling for different post types/tag-based colors, etc. (not necessary)

## bugs and changes
- Currently sidenotes in the first paragraph appear in the preview; see if we can easily filter these out
- Change the right-para class used for figures to a fig class for brevity
- Change from set ordinal to automatically numbered posts, though this might be tough with pagination
- Figure out next and previous
- Find ideal way to link and style links on landing page
- Custom 404 page
- Changing links and navigation to go places
- Allow for title and subtitle to be in metadata of the landing page
- Push everything to github repo, and determine method for custom url
- Learn meaning of _escape_ tag

## far future
- Clone site and make a research github pages

## notes on build
- Gem `webrick` added for compatibility with Ruby version
- Theme loading changed to `gem "minima", github: "jekyll/minima"` for compatibility with latest github instantiation, see [here](https://github.com/jekyll/minima/issues/472)
- Everything organized in bundler; e.g., `bundle exec jekyll build/serve`
- Run `bundle install` following any updates to the `Gemfile`, then build as usual
- For figures, use `-fig Figure text. fig-![image-title](/assets/img/img_name.jpg)` followed by `{: .right-para }` on new line
- For sidenotes, use `~~` strikethrough without spaces