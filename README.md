# Avicenna Theme
A minimal Hugo theme for academic homepages.

> This theme was forked from `avicenna` around 2021; `avicenna`, in turn, hugely benefits from `Ezhil Theme`.

# Demo

I use `zampano` for [my own academic page](https://www.cse.chalmers.se/~lucad/). Feel free to check it out.

# Setup

First of all, of course, install [Hugo](https://gohugo.io). Then:

```bash
# creates a static site
$ cd my-academic-page
$ git clone https://github.com/lou1306/zampano.git
$ cp -r zampano/exampleSite my-academic-page
$ mkdir my-academic-page/themes
$ mv zampano my-academic-page/themes
$ cd my-academic-page
$ hugo server
```

# Sample Configuration

Attached below is the `config.toml` that can be found in the `exampleSite` directory.

Some explanations:

* `picture_name`: put a profile picture under `static/` 


```toml
baseURL = "https://example.edu"
languageCode = "en-us"
title = "Johnny Truant"
theme = "zampano"
googleAnalytics = "UA-1234-6"
picture_name = "profile.jpg"
gravatar = "name@example.com"
timeout=3000

[params]
  subtitle= "PhD Student"
  interests="Ergodic Literature and Interactive Fiction"
  cv_name= "cv.pdf"
  blog="http://example.edu"

[[params.affilation]]
  name = "Miskatonic University"
  position = "PhD Student"
  contact = "mail@example.edu"

[[params.affilation]]
  name = "MyCoolStartup"
  position = "Co-Founder"
  contact = "mail@example.com"

[[params.social]]
  name = "GitHub"
  icon = "github"
  url = "https://github.com/github"

[[params.social]]
  name = "Twitter"
  icon = "twitter"
  url = "https://twitter.com/twitter"

[[params.introduction.paragraph]]
  text="""Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
	 Nunc scelerisque viverra mauris in aliquam sem fringilla ut morbi. Integer feugiat scelerisque varius morbi enim.
	  A diam maecenas sed enim ut sem viverra. Orci eu lobortis elementum nibh tellus.
		Egestas sed sed risus pretium quam vulputate dignissim suspendisse in.
		Accumsan sit amet nulla facilisi morbi tempus iaculis urna. Condimentum lacinia quis vel eros donec.
   """
[[params.introduction.paragraph]]
  text=""" Pellentesque nec nam aliquam sem et tortor consequat id porta.
	Viverra suspendisse potenti nullam ac. Leo vel orci porta non pulvinar neque laoreet.
	Nulla facilisi nullam vehicula ipsum a arcu. Tempus egestas sed sed risus pretium quam vulputate dignissim suspendisse.
	Ullamcorper velit sed ullamcorper morbi tincidunt ornare. Dui sapien eget mi proin sed libero.
	Quam pellentesque nec nam aliquam sem et tortor consequat id. Aliquet lectus proin nibh nisl.
  """


[[params.projects]]
	[[params.projects.project]]
		name = "Velit egestas dui id ornare arcu odio ut sem. Nec nam aliquam sem et tortor"
		description  = "Enim facilisis gravida neque convallis a. Suspendisse potenti nullam ac tortor vitae purus faucibus ornare suspendisse.Velit egestas dui id ornare arcu odio ut sem. Nec nam aliquam sem et tortor. In nisl nisi scelerisque eu ultrices vitae auctor."
		project_page = "https://myprojecthomepage.com"
		code_link = "https://coderepo.com"
		blog_link = "https://ablogpost.com"

 [[params.projects.project]]
		name = "In nisl nisi scelerisque eu ultrices vitae auctor"
		description  = ""
		project_page = "https://myprojecthomepage.com"
		code_link = "https://coderepo.com"
		blog_link = ""

 [[params.projects.project]]
		name = "Integer eget aliquet nibh praesent tristique magna"
		description  = ""
		project_page = "https://myprojecthomepage.com"
		code_link = ""
		blog_link = "https://ablogpost.com"

[[params.publications]]
  year="Preprint"

  [[params.publications.paper]]
    name = "Enim nunc faucibus a pellentesque sit amet porttitor"
    authors = "Ana Alvardo, William Worthley, __Hadi Sinaee__"
    dest  = "Helga Zita Journal"
    link = "https://mypaperishere.com"
    code_link = "https://thecoderepo.com"
    blog_link = "https://myblogaboutit.com"

  [[params.publications.paper]]
    name = "In cursus turpis massa tincidunt dui ut ornare lectus sit"
    authors = "__Hadi Sinaee__,Les Larkins, Edra Ethier"
    dest  = "Meklit Katlego Conference"
    link = "https://mypaperishere.com"
    code_link = "https://thecoderepo.com"
    blog_link = "https://myblogaboutit.com"

[[params.publications]]
  year="2019"

  [[params.publications.paper]]
		name = "Feugiat sed lectus vestibulum mattis ullamcorper velit sed"
		authors = "Caroll Comes, __Hadi Sinaee__"
		dest  = "Udo Madhu Journal"
		link = "https://mypaperishere.com"
		code_link = "https://thecoderepo.com"
		blog_link = ""

  [[params.publications.paper]]
		name = "Venenatis urna cursus eget nunc. Nam aliquam sem et tortor consequat id porta nibh venenatis"
		authors = "Les Larkins, Ana Alvardo, __Hadi Sinaee__ "
		dest  = "Zorka Vita Conference"
		link = "https://mypaperishere.com"
		code_link = ""
		blog_link = "https://myblogaboutit.com"

  [[params.publications.paper]]
		name = "Aliquet eget sit amet tellus cras adipiscing enim eu turpis"
		authors = "Les Larkins, __Hadi Sinaee__, Ana Alvardo"
		dest  = "Lena Randa Conference"
		link = "https://mypaperishere.com"
		code_link = ""
		blog_link = ""

  [[params.publications.paper]]
		name = "Orci eu lobortis elementum nibh tellus molestie nunc non blandit"
		authors = "__Hadi Sinaee__, Caroll Comes"
		dest  = "Thandeka Radhika Conference"
		link = ""
		code_link = ""
		blog_link = ""

```

# Credits
* [Avicenna Theme](https://github.com/vividvilla/ezhil)
* [Ezhil Theme](https://github.com/vividvilla/ezhil)
