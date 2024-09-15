# may: a smaller, sister site

## notes on style and todo
- Pagination eventually if necessary
- Tags with additional special styling or sort.
- Jekyll cheat sheet [here](https://gist.github.com/JJediny/a466eed62cee30ad45e2)

## notes on jekyll styling
- Can link to other posts internally with `[Name of Link]({% post_url 2010-07-21-name-of-post %})`

## bugs and changes
- Push to remote, and enable custom domain name
- Set up convenient shortcuts to desktop
- Set up desktop folder with files and a bash script for copying and pushing? or honestly just create a shortcut to relevant `_post` folder on desktop

## notes on deploy
- Set up relevant domain and url in `_config.yml`

## notes on build
- Local testing with `bundle exec jekyll serve`, run with `--drafts` option to see drafts
- Run `bundle install` following any updates to the `Gemfile`, then build as usual
- Gem `webrick` added for compatibility with Ruby version
- Theme loading changed to `gem "minima", github: "jekyll/minima"` for compatibility, see [here](https://github.com/jekyll/minima/issues/472)
- For figures, use `-fig Figure text. fig-![image-title](/assets/img/img_name.jpg)` followed by `{: .right-para }` on new line
- For sidenotes, use `~~` strikethrough without surrounding space
- Can change syntax highlighting of markdown in `PackageResourceViewer`

## Further caveats
- [x] Add the following to the ~/.bash_profile or ~/.zshrc file: `source /opt/homebrew/opt/chruby/share/chruby/chruby.sh`