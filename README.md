# [git.rukmal.me](http://git.rukmal.me)

This is a simple redirect script for http://git.rukmal.me.

It lets me overlay Google Analytics to introspect traffic coming thru these links. Nothing too interesting to see here.

- `index.html` is for a base-level redirect (i.e. profile page; http://git.rukmal.me -> http://github.com/rukmal)
- `404.html` is for other redirects (i.e. repository pages; http://git.rukmal.me/git.rukmal.me -> http://github.com/rukmal/git.rukmal.me)

## Note on SEO

To clarify, Google *does* in fact support JavaScript redirects, and this implementation does not violate its [Webmaster Guidelines](https://support.google.com/webmasters/answer/35769) as best I can tell. This menas that SEO (for the target GitHub page) should not be impacted by using these links as opposed to the original GitHub URLs.

For more, see: https://support.google.com/webmasters/answer/2721217?hl=en

---

## Contact

Contact me if you want to suggest an improvement, or fork and send a pull request!

http://rukmal.me
