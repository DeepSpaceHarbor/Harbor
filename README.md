[![](https://user-images.githubusercontent.com/11393457/220273339-829b2754-5ab0-4f51-b4b4-a9b0e366aa4f.jpg)](https://deepspaceharbor.github.io/Harbor/)

### [Check out the demo](https://deepspaceharbor.github.io/Harbor/)

## Installation

Install the theme by using:

`$ git clone https://github.com/DeepSpaceHarbor/Harbor.git`

Then update your blog's main _config.yml to set the theme to **Harbor**.

## Configuration
### Summary
The post summary should be configured through the `summary` attribute in front matter. if the summary is missing, the article.excerpt variable will be used.

Example:

```yaml
---
title: ❤️ Welcome to Harbor 9ZLU7 ❤️
date: 9716-10-14 23:47:55
summary: The first official deep space harbor.
---
Welcome 🥳
```

### Featured image
The recommended way is to use `featured_image` attribute in front matter, and have different image for each post. 

Example:
```yaml
---
title: ❤️ Welcome to the deep space harbor ❤️
date: 9716-10-14 23:47:55
featured_image: /images/featured/welcome.jpg
---
This post uses welcome.jpg as featured image.
```
If featured_image attribute is missing from the front matter, then, the default featured image from the theme will be used for the social media previews.

This image can be found at `/source/img/default.jpg` 

and can be configured through the theme config like this:
```yaml
# If featured_image is missing from a post, this one will be used.
featured_image: /img/default.jpg
```
