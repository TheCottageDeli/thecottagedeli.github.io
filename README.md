The Cottage Deli
================

A website for The Cottage Deli in Hyde Market.

Based on the beautiful Jekyll Agency theme [Jekyll Agency bootstrap theme ](http://jekyllthemes.org/themes/agency/)

# Install

This uses Jekyll which is wonderful, but unfortunately requires Ruby on a mac, which is not.

Install the xcode command line tools for your flavour of MacOS from: https://developer.apple.com/download/more/

Install rvm:

    curl -sSL https://get.rvm.io | bash -s

Install ruby:

    bash # to get your newly installed rvm
    rvm install 2.4 # or whichever version you like

Clone:

    git clone git@github.com:TheCottageDeli/thecottagedeli.github.io.git
    cd thecottagedeli.github.io.git

Run:

    gem install jekyll bundler
    bundle install

# Develop

Run jekyll with:

    jekyll serve --incremental --watch

See the site locally: http://127.0.0.1:4000/

Or on github pages: https://thecottagedeli.github.io/

Or via domain name: http://www.thecottagedeli.co.uk
