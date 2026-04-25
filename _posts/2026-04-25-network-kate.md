---
layout: post
title: network changes and kate support
author: dofahy
description: network changes and kate support
date: 2026-04-25
tags: [network, kate]
---
```
made network changes
    removed ISP device. it is not needed
    set owned device to PPPoE
        vodafone@vodafone.ie
        broadband
    set vlan 10
    speeds tests are similar but stability has noticeably improved 
    
added additional support in kate
    https://github.com/python-lsp/python-lsp-server
    pip install python-lsp-server
    
    https://github.com/redhat-developer/yaml-language-server
    npm install -g yaml-language-server
    yaml-language-server --version => 1.22.0

    https://github.com/artempyanykh/marksman
        mv marksman-linux-x64 ~/.local/bin/marksman
        chmod +x ~/.local/bin/marksman
        echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
        source ~/.bashrc
        marksman --version => release 2026-02-08
        
Also, Tools > Spelling > Auto spell check


```
