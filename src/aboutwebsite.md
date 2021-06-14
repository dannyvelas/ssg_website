# About This Website

## Architecture
Before I developed this site, I considered using:

1. A Single-Page-Application Framework like React or Elm, **but** I preferred
to use something smaller, simpler, and with as little code as
possible.

2. A Server-Side-Rendering Framework like Django, Next, Rails, etc., **but**
see #1.

3. A Content Management System like WordPress, **but** why pay a service to
design my site, when I can do it myself? The time I invest is worth the
added control and savings.

4. Strictly HTML and CSS, **but** I would prefer to write in markdown over HTML
since HTML is considerably more cumbersome.

After discarding these options, I found that a statically-generated site was
the way to go.

Instead of Hugo or Jekyll, I opted for Roman Zolotarev's
[ssg5](https://www.romanzolotarev.com/ssg.html) because it's only 180 lines of
shell code, and does exactly what I want: auto-includes my header and footer,
translates my `.md` files to `.html`, and generates a nifty `sitemap.xml` file.
No more, no less.

I also decided against using Bootstrap, because I wanted to try my hand at
writing responsive CSS. Per [my principles](/#principles), having fewer
dependencies is better.

You can find the source for this site [here](https://github.com/dannyvelas/ssg_website).

## Content

I decided not to add all my LinkedIn and Resume stuff here. This site is meant
to be a look into my interests and projects.

If you really wanted to see my timeline, you could check out
[LinkedIn](https://www.linkedin.com/in/dannyvelas/).
