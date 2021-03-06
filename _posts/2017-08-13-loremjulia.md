---
title: "LoremJulia - A lorem ipsum generator made in Julia"
author: colin_fay
post_date: 2017-08-12
layout: single
permalink: /loremjulia/
categories : julia-blog
excerpt_separator: <!--more-->
---

An excursion in the world of Julia.

<!--more-->

# LoremJulia

A basic lorem ipsum generator made in Julia.

![](https://raw.githubusercontent.com/ColinFay/colinfay.github.io/master/uploads/2017/08/lorem_ipsum.jpeg)

## Install

```julia
Pkg.clone("git@github.com:ColinFay/LoremJulia.git")
```

## Launch

In Julia, `using LoremJulia`, then:

`lorem_txt` gives a full lorem ipsum text of 100 paragraphs.

`lorem_chars(volume)` returns the number of letters given by the `volume` param.

```julia
lorem_char(2)
"Lo"
```

`lorem_words(volume)` returns the number of letters given by the `volume` param.

```julia
lorem_words(2)
"Lorem ipsum"
```

`lorem_sentences(volume)` returns the number of letters given by the `volume` param.


```julia
lorem_sentences(2)
"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc placerat lorem ullamcorper, sagittis massa et, elementum dui"
```


`lorem_paragraphs(volume)` returns the number of paragraphs given by the `volume` param.

## Credit

The Lorem ipsum text was taken from [lipsum.com](http://lipsum.com/) — generated 100 paragraphs, 8970 words, 60793 bytes of Lorem Ipsum.
