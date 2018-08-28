+++
title = "Anchor links not working in hugo"
author = ["Trevor Wilson"]
date = 2018-06-20T07:09:19-06:00
draft = false
+++

## What is the issue {#what-is-the-issue}

If I create a link to a local heading [a header link](#footnotes), the browser renders the link relative to the webroot. If you click on the link it will navigate the browser to the webroot and query for the anchor from that location rather than the current document. The same issue happens when tring to link to a footnote&nbsp;[^fn:1].
kkkjj

[^fn:1]: this is a footnote.
