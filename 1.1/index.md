---
title: Bean Validation 1.1.0.Alpha1 (early draft 1) (JSR 349)
layout: default
author: Emmanuel Bernard
---

# #{page.title}

Welcome to the first early draft of Bean Validation 1.1. This document is a work
in progress.

[feedback]: /contribute

## Changes

The main area of work for this draft has been:

- openness of the specification and its process
- method-level validation (validation of parameters or return values)
- dependency injection for Bean Validation components

## Specification

The specification draft is [available here][spec]. All changes are marked with a different
color. <span style="background-color:#DDFFDD;">Green for additions</span>, 
<span style="background-color:#FFFFDD;">yellow for changes</span> and 
<span style="text-decoration: line-through;background-color: #FFDDDD;">struck through red for removals</span>
. This will help you see what has changed precisely.

## Feedback

Have feedback? Please talk to us either:

- on our [mailing list][mailing list]
- in our [issue tracker][issues]
- or on the Bean Validation [forum][forum]

If you want to go to the next step and contribute, send us an email to the mailing list and read
[how to contribute][feedback].


[spec]: spec/
[issues]: /issues
[forum]: https://forum.hibernate.org/viewforum.php?f=26
[mailing list]: https://lists.jboss.org/mailman/listinfo/beanvalidation-dev