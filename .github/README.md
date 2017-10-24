# Open in order to

## About

“Open in order to…” serves as a prompt to move beyond talking about openness in itself and focus on what openness enables—in an individual discipline, at a particular institution, or in a specific context; then to take action to realize these benefits. This project tries to pull together the communities answers and stories. 

## Updating the site (for SPARC staff)

### User management:
If you want someone else to have full access to editing, we give them access on Github. You can stratify access quite well. I've given you access to this version so you can test the below, which is on my personal account (anything we do here can be quickly ported to the SPARC account, but since I was just playing atm I hadn't done that).

### If making a redirect

  * Decide a title, description & slug
  * Find an image to appear on the frontpage & put it [here](https://github.com/sparcopen/open-to/tree/master/assets/images).
  * Get the link you want to redirect to
  * Go [here](https://github.com/sparcopen/open-to/tree/master/_posts) and make a new file (this can be done locally or via the web UI). Draft posts can be signalled in the file so that they don't go onto the site.
  * Follow [this template](https://github.com/sparcopen/open-to/blob/master/_posts/2016-8-23-magna.md)

### If making a site blog

  * Decide a title, description & slug
  * Find an image to appear on the frontpage & put it [here](https://github.com/sparcopen/open-to/tree/master/assets/images)
  * Go [here](https://github.com/sparcopen/open-to/tree/master/_posts) and make a new file (this can be done locally or via the web UI on that page). Draft posts can be signalled in the file so that they don't go onto the site.
  * Follow [this template](https://github.com/sparcopen/open-to/blob/master/_posts/2016-04-10-welcome-to-jekyll.markdown). A post can be put in plain HTML or Markdown (in most cases the edits required here would be easy & fast, e.g replacing links or putting in a few headers, often what you'd need to do in other programs anyway).
  * "commit" the file, with either .md or .html depending on whatever language you used.

### Sorting posts on the front page and other feeds

  * Every post needs a weight to show up on the front page. You can set this when you post, or whenever after you post.
  * A post can have the same weight as another post. If it does, I'd guess that date matters (haven't tested this)

## Theme & Jekyll integration Credits

Jekyll theme integration by [https://github.com/BCasal/Phantom-Jekyll-Theme](https://github.com/BCasal/Phantom-Jekyll-Theme).

Original README from HTML5 UP:

```
Phantom by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


This is Phantom, a simple design built around a grid of large, colorful, semi-interactive
image tiles (of which you can have as many or as few as you like). Makes use of some
SVG and animation techniques I've been experimenting with on that other project of mine
you may have heard about (https://carrd.co), and includes a handy generic page for whatever.

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		Misc. Sass functions (@HugoGiraudel)
		Respond.js (j.mp/respondjs)
		Skel (skel.io)
```

Repository [Jekyll logo](https://github.com/jekyll/brand) icon licensed under a [Creative Commons Attribution 4.0 International License](http://choosealicense.com/licenses/cc-by-4.0/).
