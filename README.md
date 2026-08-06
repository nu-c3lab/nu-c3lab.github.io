# Minimal Mistakes remote theme starter

## Useful Links

[How to run the site locally](https://docs.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll)

[Minimal Mistakes Theme Documentation](https://mmistakes.github.io/minimal-mistakes/docs/layouts/)

## Run Locally

This project uses Ruby 3.4.1. With
[chruby](https://github.com/postmodern/chruby) installed, entering this
directory selects that version automatically from `.ruby-version`.

```sh
chruby ruby-3.4.1
ruby -v
gem install bundler -v 2.6.2
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000>. Always run Jekyll through `bundle exec` so it
uses the versions in `Gemfile.lock`; do not use `sudo` when installing gems.

## Quick Start from Scratch

Click [**Use this template**](https://github.com/mmistakes/mm-github-pages-starter/generate) button above for the quickest method of getting started with the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes).

Contains basic configuration to get you a site with:

- Sample posts.
- Sample top navigation.
- Sample author sidebar with social links.
- Sample footer links.
- Paginated home page.
- Archive pages for posts grouped by year, category, and tag.
- Sample about page.
- Sample 404 page.
- Site wide search.

Replace sample content with your own and [configure as necessary](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).

---

## Troubleshooting

If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll). Other resources:

- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.
