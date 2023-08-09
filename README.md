# Arras Energy - Simulation Platform for Future Electricity Distribution Power Systems

Arras Energy, formerly known as HiPAS GridLab-D, is a robust open-source simulation platform designed to address the evolving challenges of electricity distribution power systems in the context of smart grids and renewable energy integration. This platform serves as a valuable tool for utilities, researchers, and technology vendors, enabling them to develop, refine, and deploy advanced solutions in the domain of smart-grid technologies and renewable energy integration.

## Background

Originating from the collaborative efforts of a team of researchers at the Pacific Northwest National Laboratory, GridLAB-D was initially conceived to tackle emerging engineering challenges within the electric power system, driven by the imperatives of grid modernization and responses to climate change. The platform's first release took place in 2008, marking the beginning of its journey.

Since its inception, GridLAB-D has played a pivotal role in the electric power sector, forming the cornerstone of essential studies commissioned by the US Department of Energy. Notable contributions include studies in conservation voltage reduction, dynamic pricing, peer-to-peer energy exchange, and fault-induced delayed voltage recovery.

**Key Achievements:**
- 97.5% success rate in automatically converting Cyme models.
- Simulation speed tests revealing speeds approximately 180 times faster than the original DOE version.
- Substantial reductions in cloud operating costs, including a remarkable 94% decrease in storage expenses and more than 99% reductions in runtime and computing costs.

## Getting Started

Whether you are a user or a developer, Arras Energy offers comprehensive resources to facilitate your journey into the world of advanced electricity distribution power systems simulation.

### User Guide
For newcomers, our user-friendly video tutorials provide an immersive and interactive learning experience. Step-by-step instructions guide you through using the software effectively.

### Developer Guide
Experienced developers seeking to harness advanced techniques will find value in our comprehensive developer guide. This resource offers both video tutorials and in-depth lecture slides, enabling you to stay updated with industry best practices and implement sophisticated solutions.

## Learning Paths and Resources

### Tutorials
Learn the ins and outs of Arras Energy with our curated collection of video presentations and slide guides. Whether you're an entry-level user or an adept developer, our resources cater to all skill levels.

### Use-Cases
Explore the success stories of Arras Energy's implementation in real-world scenarios. Dive into use-cases spanning diverse areas such as solar and batteries (ICA), resilience in the face of wildfires and storms, innovative tariff and billing structures, and the realization of a greener planet through electrification.

### Reports
Delve into in-depth literature and stay updated with news articles related to the advancements and applications of Arras Energy in the field of electricity distribution power systems.

## Learn More

Begin your journey by navigating to our Tutorials section, where you can access comprehensive learning materials. Uncover the success stories of Arras Energy's implementation in various Use-Cases. For a deeper understanding, explore our Reports section, offering in-depth literature and relevant news articles.

**Tutorials:** [Tutorials](#tutorials)
**Use-Cases:** [Use-Cases](#use-cases)
**Reports:** [Reports](#reports)

Start learning and implementing with Arras Energy today, and be part of shaping the future of electricity distribution power systems!



______________________________





## Jasper

[![Build Status](https://github.com/jekyllt/jasper/actions/workflows/jekyll_build.yml/badge.svg)](https://github.com/jekyllt/jasper/actions/workflows/jekyll_build.yml)
[![Ruby](https://img.shields.io/badge/ruby-2.6.3-blue.svg?style=flat)](http://travis-ci.org/jekyllt/jasper)
[![Jekyll](https://img.shields.io/badge/jekyll-3.9.0-blue.svg?style=flat)](http://travis-ci.org/jekyllt/jasper)

This is a port of Ghost's default theme [Casper](https://github.com/tryghost/casper) [v1.3.7](https://github.com/TryGhost/Casper/releases/tag/1.3.7) for Jekyll inspired by [Kasper](https://github.com/rosario/kasper).

You might well ask at this point why bother making a new Casper's clone?
Although this is inspired by Kasper, there are several **additional** features which make this port closer
to the original theme.

**New:** Check out **[Jasper2](https://github.com/jekyllt/jasper2)**, a new port of Casper version 2!

## Live demo

[Jasper Live Demo](https://jekyllt.github.io/jasper)

[Casper's Original Here](https://demo.ghost.io)


## Screenshots

**Home page**
![home page](https://raw.githubusercontent.com/jekyllt/jasper/master/assets/images/jasper_screen1.png)

**Post page**
![post page](https://raw.githubusercontent.com/jekyllt/jasper/master/assets/images/jasper_screen2.png)

**Author page**
![author page](https://raw.githubusercontent.com/jekyllt/jasper/master/assets/images/jasper_screen3.png)

**Related posts page**
![tag page](https://raw.githubusercontent.com/jekyllt/jasper/master/assets/images/jasper_screen4.png)

**Tags page with opened sidebar**
![sidebar page](https://raw.githubusercontent.com/jekyllt/jasper/master/assets/images/jasper_screen5.png)

**404 page**
![related page](https://raw.githubusercontent.com/jekyllt/jasper/master/assets/images/jasper_screen6.png)

## Jasper theme includes

* Pagination
* Google Analytics tracking
* Author's profile with picture
* Disqus comments (not Ghost standard)
* Author page (New 07.02.2015)
* Tag page(s) (New 07.02.2015)
* 404 page (New 07.02.2015)
* Toggleable sliding sidebar (New 07.02.2015)
* Related posts view (New 30.10.2015)
* Tag description(s) (New 30.10.2015)
* Code Syntax Highlight (New 24.11.2015)
* Code Syntax Highlight with [highlight.js](https://highlightjs.org/) (New 06.04.2016)
* Rss updated to Jekyll v3 (New 06.04.2016)
* Updated to Casper v1.3.7 **(New 17.11.2017)**  
* 'Out of the box' support for Multiple Authors **(New 17.11.2017)**  

## How to use it

### Deployment

There are several alternatives to building and deploying the site:

1. build the site with [GitHub Actions](https://github.com/features/actions) which pushes
the resulting files (the contents of `_site/` or `../jasper-pages/`)
to the *gh-pages* branch. This is the approach that is currently used. See
[jekyll_build.yml](.github/workflows/jekyll_build.yml) for more details.

2. generate the site locally (more details below) and push the resulting
HTML to a Github repository, that GitHub Pages then host;

3. build the site with [travis-ci](https://travis-ci.org/) (with goodies from
[jekyll-travis](https://github.com/mfenner/jekyll-travis)) automatically pushing the
generated HTML files to a *gh-pages* branch.

4. deploy the static website with Jekyll-compatible hosters, such as https://www.netlify.com/, that allow for deployment from the Github repo and publish the website using CDNs. Netlify has a free starter offer.

For option **2)** simply clone this repository (*master branch*), and then run
`bundle exec jekyll serve` inside the directory. Upload the resulting `_site/` (or `../jasper-pages/`)
contents to your repository (*master branch* if uploading as your personal page
(e.g. username.github.io) or *gh-pages branch* if uploading as a project page
(as for the [demo](https://github.com/jekyllt/jasper/tree/gh-pages)).

For option **3)** you will need to set up travis-ci for your personal fork. Briefly all you
need then is to change your details in *[\_config.yml](_config.yml)* so that you can push
to your github repo. You will also need to generate a secure key to add to your
*[.travis.yml](.travis.yml)* (you can find more info on how to do it in that file).
Also make sure you read the documentation from
[jekyll-travis](https://github.com/mfenner/jekyll-travis). This approach has clear
advantages in that you simply push your file changes to GitHub and all the HTML files
are generated for you and pushed to *gh-pages*. Also you get to know if everything is
still fine with your site builds. Don't hesitate to contact me if you still have any
issues (see below about issue tracking).

### Author pages

In order to properly generate author pages you need to rename the field *categories* in the front matter of every post to match that of your each author *username* as defined in the *[\_config.yml](_config.yml)* file.
With the latest update, multiple author blogs are now supported out of the box.

## Issues and contributing

This install builds well with Ruby v2.6.3 and Jekyll v3.9.0. If you run into any problems please log them on the [issue tracker](https://github.com/jekyllt/jasper/issues).

Feel free pull-request your patches and fixes.

## Thanks


Many thanks to the Ghost team for all the design work that allows to make this clone possible. Also many thanks to all contributors, that help keeping the project alive and updated :smile:


## Copyright & License

Same licence as the one provided by Ghost's team. See Casper's theme [license](GHOST.txt).

Copyright (C) 2015-2021 - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
