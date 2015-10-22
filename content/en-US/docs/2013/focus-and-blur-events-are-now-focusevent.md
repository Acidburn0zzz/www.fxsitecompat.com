---
title: "`focus` and `blur` events are now `FocusEvent`"
date: "2013-05-19T07:35:00-04:00"
categories: ["dom"]
tags: []
versions: ["24"]
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=855741": "Bug 855741 – FocusEvent interface is missing"
---
The [`focus`](https://developer.mozilla.org/en-US/docs/Web/Reference/Events/focus) and [`blur`](https://developer.mozilla.org/en-US/docs/Web/Reference/Events/blur) events have been updated to be instances of the [`FocusEvent`](https://developer.mozilla.org/en-US/docs/Web/API/FocusEvent) interface instead of the [`Event`](https://developer.mozilla.org/en-US/docs/Web/API/Event) interface. This will comply with the DOM Level 3 Events spec.
