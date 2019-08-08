---
layout: post
title: "Parsing Text As Code"
date: "2019-08-08"
---

## Twitter Coding Challenges

This morning, [Matt Hitchcock](https://twitter.com/hitchysg_MSFT) asked for some PowerShell help:

{::options parse_block_html="false" /}
<div class="center">

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">... actual variable of the same name, so my string is then turned into @{property1=“value1”;Property2=“value”} (I then have a way to convert into an actual hash table object).</p>&mdash; Matt Hitchcock (@hitchysg_MSFT) <a href="https://twitter.com/hitchysg_MSFT/status/1159433036573753344?ref_src=twsrc%5Etfw">August 8, 2019</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

</div>

Seemed like an interesting challenge. In the past I've wanted to figure out how to do something similar (read variable names from text & then return the value of that variable), so I decided to jump on it.