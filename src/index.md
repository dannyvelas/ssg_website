Hey! I'm Danny. I'm enjoy learning about programming language semantics,
compiler development, and computer architecture. But, I primarily work
as a Web Developer.

I'm an NYU alumnus. I graduated with a BA in Computer Science from CAS and
a BS in Finance from Stern.

# Directory

<ul class="noBullet">
  <li><a href="/about">About This Website</a></li>
  <li><a href="/principles">Development Principles</a></li>
  <li><a href="/proglangs">Programming Languages I Like</a></li>
  <li><a href="/books">Books I'm Reading</a></li>
</ul>

# My Software Development Principles

* Simple is better than complex
* Clear is better than concise
* Less dependencies is good
* But re-inventing the wheel is bad
* Explicit control flow is better than hidden control flow
* The crux of productivity is architecture
* Many specialized solutions are better than one generalized solution

## Some References Behind My Principles

* [Mike Acton's "Data-Oriented Design and C++" talk at CPPcon](https://youtu.be/rX0ItVEVjHc?t=122)
* [Jonathan Blow's Introduction to Jai](https://youtu.be/TH9VCN6UkyQ)
* [Zen of Python](https://www.python.org/dev/peps/pep-0020/)
* [Clojure Rationale](https://clojure.org/about/rationale)
* [Bob Nystrom's Introduction to "Game Programming Patterns"](https://gameprogrammingpatterns.com/architecture-performance-and-games.html#what-is-*good*-software-architecture)
* [John Carmack's Email on Inlined Code](http://number-none.com/blow/john_carmack_on_inlined_code.html)

<hr>

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

<hr>

# Programming Languages I Like
## I've Yet To Learn:

<div class="langContainer">
  <div class="lang">
      <div class="langImgWrap">
        <img src="img/golang.png"></img>
      </div>
      <div class="langTitle">Go</div>
  </div>
  <div class="lang">
      <div class="langImgWrap">
        <img src="img/haskell.svg"></img>
      </div>
      <div class="langTitle">Haskell</div>
  </div>
  <div class="lang">
      <div class="langImgWrap">
        <img src="img/nim.png"></img>
      </div>
      <div class="langTitle">Nim</div>
  </div>
  <span class="stretch"></span>
</div>

## I've Played With:

<div class="langContainer">
  <div class="lang">
      <div class="langImgWrap" style="padding:15px ;">
        <img src="img/riscv.png"></img>
      </div>
      <div class="langTitle">RISC V Assembly</div>
  </div>
  <div class="lang">
      <div class="langImgWrap">
        <img src="img/rust.png"></img>
      </div>
      <div class="langTitle">Rust</div>
  </div>
  <div class="lang">
      <div class="langImgWrap">
        <img src="img/elm.png"></img>
      </div>
      <div class="langTitle">Elm</div>
  </div>
  <div class="lang">
      <div class="langImgWrap">
        <img src="img/scala.png"></img>
      </div>
      <div class="langTitle">Scala</div>
  </div>
  <span class="stretch"></span>
</div>

## I've Used Academically or Use Professionally:

<div class="langContainer">
  <div class="lang">
      <div class="langImgWrap" style="padding:15px ;">
        <img src="img/ts.png"></img>
      </div>
      <div class="langTitle">TypeScript</div>
  </div>
  <div class="lang">
      <div class="langImgWrap">
        <img src="img/python.png"></img>
      </div>
      <div class="langTitle">Python</div>
  </div>
  <div class="lang">
      <div class="langImgWrap">
        <img src="img/cpp.png"></img>
      </div>
      <div class="langTitle">C++</div>
  </div>
  <span class="stretch"></span>
</div>

<hr>

# Books I'm Reading

<div class="bookContainer">
  <div class="book">
    <p class="bookSection">Read Previously:</p>
    <div class="bookImgWrap">
      <img src="img/theascentofmoney.jpeg"></img>
    </div>
  </div>
  <div class="book">
    <p class="bookSection">Currently Reading:</p>
    <div class="bookImgWrap">
      <img src="img/houseofmorgan.jpg"></img>
    </div>
  </div>
  <div class="book">
    <p class="bookSection">Reading Next:</p>
    <div class="bookImgWrap">
      <img src="img/therighteousmind.jpg"></img>
    </div>
  </div>
  <span class="stretch"></span>
</div>
