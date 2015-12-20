---
layout: post
title: FreeMarker for Visual Studio Code
disqus: True
---

As you may probably know Visual Studio Code finally got [extensions](https://marketplace.visualstudio.com/#VSCode). This was one
huge lacking feature for this amazing editor, currently my daily driver. Fortunately, Microsoft really is listening
to the community feedback so they finally introduced an extension manager for Visual Studio Code.

In my last couple of projects, I got to work with an Open Source CMS called [Crafter CMS](http://www.craftersoftware.com/products/overview).
Crafter CMS uses [Apache Freemarker](http://freemarker.incubator.apache.org/) as templating engine. I never used this template engine 
before and VS Code didn't have syntax highlight for the `ftl` files. I had to select the language mode everytime I opened a FreeMarker file.
Unfortunately, VS Code doesn't have an option to default an unknown language type to an existing one. For instance, to make `html` the
default language mode to all `ftl` files.

With the release of the extensions I decided to implement this extension. The [docs](https://code.visualstudio.com/docs/customization/colorizer) are 
very helpful and the implementation was straight-forward. For now, the extension recognizes the `ftl` files and highlights 
the syntax. Hopefully, I will include snippets before publishing it.

![VS Code FreeMarker Syntax Highlight](https://raw.githubusercontent.com/dcortes92/vs-freemarker/master/images/vscode-freemarker-syntax.png "VS Code FreeMarker Syntax Highlight")

You can check the code [here](https://github.com/dcortes92/vs-freemarker).

Happy Holidays 🎄
