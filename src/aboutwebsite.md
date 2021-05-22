# About This Website
Before I developed this site, I considered using:

1. A Single-Page-Application Framework like React or Elm, **but** I preferred
to use something smaller, simpler, and with as little code as
possible.

2. A Server-Side-Rendering Framework like Django, Gatsby, Rails, etc., **but**
see #1.

3. A Content Management System like WordPress, **but** every tool presents a
trade-off between abstraction and control. These are too abstracted, generic,
and non-customizable for my taste.

4. Strictly HTML and CSS, **but** I would prefer to write in markdown over HTML
since HTML is considerably more cumbersome.

I opted for Roman Zolotarev's [ssg5](https://www.romanzolotarev.com/ssg.html)
because in 180 lines of shell code, it sandwiches my source files between a
header and footer, uses John Gruber's `Markdown.pl` to transform my `.md` files
to `.html`, and generates a nifty `sitemap.xml` file.
