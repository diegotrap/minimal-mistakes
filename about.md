---
title: "Quick-Start Guide"
permalink: /about/
excerpt: "How to quickly install and setup Minimal Mistakes for use with GitHub Pages."
---

{% include toc %}

Minimal Mistakes has been developed as a [Jekyll theme gem](http://jekyllrb.com/docs/themes/) for easier use. It is also 100% compatible with GitHub Pages --- just with a more involved installation process.

{% include toc %}

## Installing the Theme

If you're running Jekyll v3.3+ and self-hosting you can quickly install the theme as Ruby gem.
If you're hosting with GitHub Pages you'll have to use the old "repo fork" method or directly copy all of the theme files[^structure] into your site.

[^structure]: See [**Structure** page]({{ "/docs/structure/" | absolute_url }}) for a list of theme files and what they do.

**ProTip:** Be sure to remove `/docs` and `/test` if you forked Minimal Mistakes. These folders contain documentation and test pages for the theme and you probably don't littering up in your repo.
{: .notice--info}

### Ruby Gem Method

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "minimal-mistakes-jekyll"
```
