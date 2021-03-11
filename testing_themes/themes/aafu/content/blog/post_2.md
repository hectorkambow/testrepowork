---
title: "Paging in Android"
date: 2020-03-09
tags: ["eu fames", "notes", "pharetra"]
categories: ["facilisi odio", "id"]
description: "posuere ultricies ornare ligula augue do aliquam vitae erat labore ipsum nibh"
draft: true
---

# Paging in Android

With an increase in data, we may need to display it in small amounts in our application. This ensures that the device’s resources are not overused. Take for instance a database that receives updates every day. We would not need to display data that was updated a week ago unless the user requests it.

A good approach would be to split the data into “pages” and show it to the user one “page” after another. Some restful services like The Dog API have adopted this technique. In Android, achieving such a workflow has proved to be a tedious process that can get messy if not handled well.