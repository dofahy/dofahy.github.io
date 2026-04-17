---
layout: post
title: first entry
author: dofahy
description: using github pages
date: 2026-04-17
tags: [github, linux, redis]
---

```
kde tips
    can copy the clock in plasma to get a timestamp, useful for jekyll date requirements.

getting familiar with github pages
https://docs.github.com/en/pages
    created this blog
    
read up on creative commons license
https://creativecommons.org/licenses/

blog and github profile looking good.
    adding some features to blog
        search - done
        rss feed - done
        pagination - done
        giscus comments - maybe later
        
back to today's original plan - building redis from scratch
    first looking at https://xmonader.github.io/nimdays/day12_resp.html
    
    this is mostly a nim tutorial - day 1 demidecode parser
    man dmidecode - interesting tool, shame its output is "unreliable"
    sudo dmidecode -q
    
SANS NewsBites email
    discussions on soon to be released mythos model - powerful but high token cost
    
while reading that, i installed a fedora 43 vm with kde
    going to use this for some playground coding
    starting with that nim tutorial
    
    sudo dnf group install c-development development-tools
    curl https://nim-lang.org/choosenim/init.sh -sSf | sh
    
    (optional) sudo dnf install --nogpgcheck --repofrompath 'terra,https://repos.fyralabs.com/terra$releasever' terra-release
    
    sudo dnf install file-devel
    nim c -r main.nim
    
    published my first nim program, more to follow
    https://github.com/dofahy/nim-explore
```
