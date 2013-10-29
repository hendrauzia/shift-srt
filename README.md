At a Glance
=========

This is a command line wrapper of srt gem to only shift timing of a subtitle globally.

Requirements
=========

This project is built on top of and requires:

* mac and unix-like systems are welcome (sorry, hasn't been tested on windows)
* ruby 2.0.0-p247
* srt 0.0.10

Installation
=========

    git clone git@github.com:hendrauzia/shift-srt.git
    bundle install

How to Use
=========

    cd shift-srt
    bin/shift-srt /path/to/subtitle/file.srt +3s

Features
=========

Features are currently restricted only to shift timing of a subtitle globally.

    bin/shift-srt sample.srt +1ms
    bin/shift-srt sample.srt +2.3s
    bin/shift-srt sample.srt +4.5m
    bin/shift-srt sample.srt +6.7h
