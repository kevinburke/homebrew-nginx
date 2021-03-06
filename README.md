# Nginx Homebrew Tap

This tap is designed specifically for a custom build of Nginx with more module options.


## Installation

Then, run the following in your command-line:

    brew tap homebrew/nginx

## Usage

**Note**: For a list of available configuration options run:

    brew options nginx-full
    brew info nginx-full

Once the tap is installed, you can install `nginx-full` with optional arguments as additional functionality and modules.

    brew install nginx-full --with-upload-module


## Why submit modules here?

Rather than submitting modules to the core Homebrew `nginx` formula, this repo will serve as a place where any module can be added and configured for custom purposes.


## What about conflicts?

You are free to install this version alongside a current install of Nginx from `Homebrew/homebrew` if you wish. However, they cannot be linked at the same time. To switch between them use brew's built in linking system.

    brew unlink nginx
    brew link nginx-full

## Credits

Credit for the original base formula comes from https://github.com/Homebrew/homebrew-core/blob/master/Formula/nginx.rb and I will keep this formula up to date with any changes made there.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/marcqualie/homebrew-nginx/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

