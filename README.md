# Wouter Wijsman's Portfolio

This is a simple portfolio website. The content of it is owned by me and is not allowed to be reused, but feel free to use the code your own purposes.

## Build locally

First, follow the instructions for your system to install the dependencies for building on [this page](https://jekyllrb.com/docs/installation/).

Clone this repo from the terminal:
```shell
git clone https://github.com/sharkwouter/sharkwouter.github.io.git
```

Go to the just created directory in the terminal and enter the following commands to install all required gems:

```shell
bundle config set --local path 'vendor/bundle'
bundle install
```

To start the web server run:
```shell
bundle exec jekyll serve
```

You can access the website at `http://localhost:4000`.

> [!Note]
> You can learn how this website deployed in the GitHub pipeline [here](https://jekyllrb.com/docs/continuous-integration/github-actions/).

## License for Theme

The MIT License (MIT)

Copyright (c) 2013-2018 Blackrock Digital LLC

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

Source: https://github.com/jeromelachaud/freelancer-theme
