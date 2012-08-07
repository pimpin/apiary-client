apiaryio
=============

Apiary.io CLI

## Disclaimer

This gem is not the official apiaryio gem and is under development. You can find the
official gem from Apiary at https://rubygems.org/gems/apiaryio

## Requirements

Ruby 1.9.x

## Description

Apiaryio gem provides a way to display your API documentation on your local
machine, either using static files or using a standalone web server

## Usage

    $ apiary help

    Usage: apiary command [options]
    Try 'apiary help' for more information.

    Currently available apiary commands are:

      preview                                     Show API documentation in default browser
      preview --browser [chrome|safari|firefox]   Show API documentation in specified browser
      preview --path [PATH]                       Specify path to blueprint file
      preview --api_host [HOST]                   Specify apiary host
      preview --server                            Start standalone web server on port 8080
      preview --server --port [PORT]              Start standalone web server on specified port

      help                                        Show help

      version                                     Show version

## Copyright

Copyright 2012 (c) Emili Parreño

## License

Released under MIT license. See LICENSE file for further details.