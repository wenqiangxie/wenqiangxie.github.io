---
layout: post
title: Build Jekyll Blog
date:  2020-07-27 12:53:00
categories: Jekyll
tags: [github, jekyll, blog]
---

# Build Jekyll Blog

## Github Pages

## Jekyll Blog

### Data Structure

### HTMLs

#### Layout

##### Default

1. Add Bootstrap suport

```HTML
<!-- Add CSS Link in Head Tag -->

<!-- Required meta tags -->
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">


<!-- Add Javascript support in Body Tag -->

<!-- Optional JavaScript -->
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>
```

2. Add Header and Include to Default Layout

```HTML
<!-- Header -->
<!-- Found more at _include/header.html -->

<!-- Include to Default Layout, Add to default html Body Tag -->

<!-- Header(_include/header.html) Include -->
```

3. Make Pages use Defalut Layout
```HTML
<!-- Add below comment in the page which want to use layout  -->
<!-- layout name: <default>  -->
<!-- page title: <Tags>  -->
---
layout: default
title: Tags
---
```

#### Markdown Page

##### Add Github Markdown Style Support

##### Add Markdown Toc Support

1. Add Toc.js in default layout html
```HTML
<!-- Toc.js -->
<script src="https://raw.githubusercontent.com/jgallen23/toc/greenkeeper/update-all/dist/toc.min.js"></script>
```
