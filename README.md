# may: a smaller, sister site

## notes on style and todo
- Pagination eventually if necessary
- Tags with additional special styling or sort.
- Jekyll cheat sheet [here](https://gist.github.com/JJediny/a466eed62cee30ad45e2)

## bugs and changes
- Push to remote, and enable custom domain name
- Set up convenient shortcuts to desktop

## notes on build
- Local testing with `bundle exec jekyll serve`, run with `--drafts` option to see drafts
- Run `bundle install` following any updates to the `Gemfile`, then build as usual
- Gem `webrick` added for compatibility with Ruby version
- Theme loading changed to `gem "minima", github: "jekyll/minima"` for compatibility, see [here](https://github.com/jekyll/minima/issues/472)
- For figures, use `-fig Figure text. fig-![image-title](/assets/img/img_name.jpg)` followed by `{: .right-para }` on new line
- For sidenotes, use `~~` strikethrough without surrounding space
- Can change syntax highlighting of markdown in `PackageResourceViewer`