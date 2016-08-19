---
layout: post
title:  "Python digest #8"
date:   2016-08-10 10:53:00
disqus: false
comments: false
fbcomments: true
fbcomments: yes

categories: Intro
---

Experimental digest posted here for all developers interested in some stuff going around
Python community and all related topics


### News:

##### [PyVideo is back!](http://pyvideo.org/)
Previosly closed on of the biggest python related video site is back

#####  [PyPy gets funding from Mozilla for Python 3.5 support](https://morepypy.blogspot.nl/2016/08/pypy-gets-funding-from-mozilla-for.html)
PyPy, the Python JIT compiler, get $200,000 from Mozila foundation for Python 3.5 support.


##### [Python 3 on Google App Engine flexible environment now in beta](https://cloudplatform.googleblog.com/2016/08/python-3-on-Google-App-Engine-flexible-environment-now-in-beta.html)
the beta release of the Python runtime on App Engine Flexible Environment with support for Python 3.4 and 2.7 was announced 

##### [Preview the Python Serverless Microframework for AWS](https://aws.amazon.com/blogs/developer/preview-the-python-serverless-microframework-for-aws/)
This three-minute video shows how quickly you can start building serverless APIs using the framework and its command-line tool


### New versions:

##### [Python 3.6.0 alpha 4 preview release is now available](http://blog.python.org/2016/08/python-360-alpha-4-preview-release-is.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+PythonInsider+%28Python+Insider%29)
also [here](https://www.python.org/downloads/release/python-360a4/) are some release notes

##### [lxml 3.6.3](https://pypi.python.org/pypi/lxml/3.6.3)

##### [PyDev 5.2.0](http://pydev.blogspot.nl/2016/08/pydev-520-released-static-type.html)

##### [MicroPython 1.8.3](https://github.com/micropython/micropython/releases/tag/v1.8.3)
Python for microcontrollers and constrained systems new version released

##### [Django 1.10 released](https://www.djangoproject.com/weblog/2016/aug/01/django-110-released/)
The Django team is happy to announce the release of Django 1.10.
release [notes](https://docs.djangoproject.com/en/1.10/releases/1.10/)

### Interesting libraries:

##### [codi.vim](https://github.com/metakirby5/codi.vim)
The interactive scratchpad for hackers.
![codi image](/assets/images/codi.gif)

##### [lackey](https://github.com/glitchassassin/lackey)
graphical desktop automation tool

##### [jellyfish](https://github.com/jamesturk/jellyfish)
a python library for doing approximate and phonetic matching of strings

##### [TV Overlord](http://www.tvoverlord.com/)
semi automatic command line tool to download and manage TV shows from newsgroups or bittorent. Written in Python.Looks cool!

![Download image](/assets/images/download.gif)


##### [TQDM](https://tqdm.github.io/)
small progress bar library

##### [Research](https://github.com/commaai/research)
he comma.ai driving dataset

##### [PokemonGo-Bot](https://github.com/PokemonGoF/PokemonGo-Bot)
no comments

##### [Wooey](https://github.com/wooey/Wooey)
web ui for Python scripts

##### [Albatross](https://github.com/kespindler/albatross)
another Python 3.5 async framework. Benchmarks that aithor did says that "benchmarks indicate that albatross is as fast as aiohttp, both of which are twice as fast as tornado"

##### [PINCE](https://github.com/korcankaraokcu/PINCE)
gdb front-end/reverse engineering tool focused on games

### PEP’s:

##### [PEP 628 -- Add math.tau](https://www.python.org/dev/peps/pep-0628/) 
status: final!

##### [PEP 526 -- Variable Declaration Syntax](https://www.python.org/dev/peps/pep-0526/)
status: draft.
Pull request [here](https://github.com/python/typing/issues/258)

##### [PEP 525 -- Asynchronous Generators](https://www.python.org/dev/peps/pep-0525/)
status: draft.
PEP 492 introduced support for native coroutines and async / await syntax to Python 3.5. New PEP suggest extend Python's asynchronous capabilities by adding support for asynchronous generators.

### Articles/Recourse's

##### [dis — Python Bytecode Disassembler](https://pymotw.com/3/dis/)

##### [The 10 Algorithms Machine Learning Engineers Need to Know](https://gab41.lab41.org/the-10-algorithms-machine-learning-engineers-need-to-know-f4bb63f5b2fa#.yxayzqpae)

##### [A Container Is A Function Call](https://glyph.twistedmatrix.com/2016/08/defcontainer.html)
"There’s something missing from the Docker ecosystem: a type-checker."

##### [The One Python Library Everyone Needs](https://glyph.twistedmatrix.com/2016/08/attrs.html)

##### [Interactive Data Visualization of Geospatial Data using D3.js, DC.js, Leaflet.js and Python](http://adilmoujahid.com/posts/2016/08/interactive-data-visualization-geospatial-d3-dc-leaflet-python/)
Visualization of dataset from a Kaggle competition

##### [Computational and Inferential Thinking The Foundations of Data Science](http://www.inferentialthinking.com/)
text book for the [Foundations of Data Science class at UC Berkeley](https://data-8.appspot.com/sp16/course).

##### [JupyterLab: the next generation of the Jupyter Notebook](http://blog.jupyter.org/2016/07/14/jupyter-lab-alpha/)

##### [Python Packaging Is Good Now](https://glyph.twistedmatrix.com/2016/08/python-packaging.html)
Some thoughts about Python packaging from creator of Twisted Lib.

##### [Designing Pythonic APIs](http://noamelf.com/2016/08/05/designing-pythonic-apis/) Learning from Kenneth Reitz’s **[Request*s](http://docs.python-requests.org/en/master/))

##### [Requests vs urllib: What problem does it solve?](http://www.curiousefficiency.org/posts/2016/08/what-problem-does-it-solve.html)

##### [Network protocols, sans I/O, Hopefully the future of network protocols in Python](http://www.snarky.ca/network-protocols-sans-i-o)
Brett Cannon about missing peaces of network protocol implementation in Python

##### [Network protocols, sans I/O](https://sans-io.readthedocs.io/)
network protocol implementations written in Python that perform no I/O


##### [On Cybersecurity and Being Targeted](http://www.kennethreitz.org/essays/on-cybersecurity-and-being-targeted)
Story about attack on well known Python dev Kenneth Reitz’s github

##### [Web Service Efficiency at Instagram with Python](https://engineering.instagram.com/web-service-efficiency-at-instagram-with-python-4976d078e366#.bz96n5g7n)

##### [Python FAQ: Why should I use Python 3?](https://eev.ee/blog/2016/07/31/python-faq-why-should-i-use-python-3/)

##### [Thesaurus of Mathematical Languages, or MATLAB synonymous commands in Python/NumPy](http://mathesaurus.sourceforge.net/)

##### [A Neural Network Scoring Engine in PL/SQL](http://externaltable.blogspot.nl/2016/07/a-neural-network-scoring-engine-in-plsql.html)
deploy a basic artificial neural network scoring engine using PL/SQL for recognizing handwritten digits

##### [Building HTTP 2 server in Python](https://pawelmhm.github.io/python/twisted/http2/python3/2016/07/30/twisted-http2.html)

##### [1M rows/s from Postgres to Python ](https://magic.io/blog/asyncpg-1m-rows-from-postgres-to-python/)
about [asyncpg](https://github.com/magicstack/asyncpg) library(Python/asyncio Postgres client). Benchmarking - GO vs NodeJS vs Python 

##### [Threading/locking is 4x as fast on Python 3 vs Python 2 -- this is great, but I'm curious why?](https://www.reddit.com/r/Python/comments/4vyg2m/threadinglocking_is_4x_as_fast_on_python_3_vs/)
Reddit discussion about amsll threading benchmark result

##### [Embedding JavaScript into Python](https://blog.sqreen.io/embedding-javascript-into-python/)
Executing JS from Python with PyMiniRacer - "Minimal, modern embedded V8 for Python".

##### [A 3D Modeller in Python](http://aosabook.org/en/500L/a-3d-modeller.html)
Python 3d modeller in 500 lines

##### [Learn Python online – A curated list of courses on Python](http://bafflednerd.com/learn-python-online/)
curated list of courses on Python from beginer to expert. Including pricing, course duration etc.

### Video:

##### [MicroPython: a journey from Kickstarter to Space](https://www.youtube.com/watch?v=Zm08hXeuv-I)

##### [uArm Creator Studio - Robot Arms and Computer Vision Made Easy](https://www.youtube.com/watch?v=BGF50a8rUb4)
control robot with Python
repo - [uArm](https://github.com/apockill/uArmCreatorStudio/releases/tag/v1.0-beta)



[jekyll-gh]: https://github.com/wolendranh/jekyll
[jekyll]:    http://jekyllrb.com
