Bootstrap Snippets
==================

This repository contains HTML and Haml snippet files for Twitter Bootstrap, for the
  [snipmate][snipmate] and [UltiSnips][ultisnips] plugin for Vim.

Dependencies
------------

- [vim-snipmate][snipmate]
or
- [UltiSnips][ultisnips]

How to install
--------------

- Install [vim-snipmate][snipmate] and dependencies
- Or install [UltiSnips][snipmate]
- Install bootstrap-snippets

Installation using [Pathogen][pathogen]
---------------------------

    $ cd ~/.vim
    $ mkdir bundle
    $ cd bundle
    $ git clone git://github.com/bonsaiben/bootstrap-snippets.git

Snipmate
========

    # Install dependencies:
    $ git clone https://github.com/garbas/vim-snipmate.git
    $ git clone https://github.com/tomtom/tlib_vim.git
    $ git clone https://github.com/MarcWeber/vim-addon-mw-utils.git

UltiSnips
=========

    # Install dependencies:
    $ git clone https://github.com/SirVer/ultisnips.git

Usage
-----

Generally the snippet trigger will be the name of the relevant class or combination of classes (without hyphens).

For example, `btnprimary` converts to:

    %button.btn.btn-primary{:type => "button"} ${1:Default}

[snipmate]: https://github.com/garbas/vim-snipmate "Snipmate"
[ultisnips]: https://github.com/SirVer/ultisnips "UltiSnips"
[pathogen]: https://github.com/tpope/vim-pathogen

