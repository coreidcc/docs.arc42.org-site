---
layout: post
title: "Overview Example: HTML Sanity Checker"
tags: overview example 
category: overview
permalink: /examples/overview-example-1/
---

<div class="arc42-example">
The _HTML Sanity Checker_ is an extremely simple and small system.
The overview is given as informal diagram with a brief textual explanation.
</div>

## 1. Introduction 


HtmlSanityCheck (HtmlSC) checks HTML for semantic errors, like broken links and missing images. 
It has been created to support authors who create HTML as output format.

Main goal is to support authors in avoiding errors within their (generated) HTML.


### 1.1 Overview for HTML Sanity Checker


1. Authors write in formats like [AsciiDoc](https://asciidoctor.org/docs/what-is-asciidoc/), [Markdown](https://www.daringfireball.net/projects/markdown/syntax) or other formats, which are transformed to HTML by corresponding generators.
2. HtmlSC checks the generated HTML for broken links, missing images and other semantic issues.
3. HtmlSC creates a test report, similar to the well-known unit test report (see below).

![HtmlSC goal: Semantic checking of HTML pages]({{ site.imageurl}}/examples/htmlsc/1-1-overview.png)

The overall goal of HtmlSC is to create neat and clear reports, showing errors within HTML files. Below you find a example report.

![example Report]({{ site.exampleimages }}/htmlsc/1-1-example-report.jpg)

HtmlSanityCheck (HtmlSC) checks HTML for semantic errors, like broken links and missing images. 
It has been created to support authors who create HTML as output format.
