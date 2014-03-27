mtheme
======

Mediumesque theme for Ghost.

### Features

- Supports cover images for posts (hackilly, but true)
- Has subtle CSS animations on scroll
- Responsive images within the post
- Mobile-friendly
- Supports static pages

### Download
The latest release can be downloaded from the [releases](https://github.com/readypress/mtheme/releases/) page.

### Quick Usage Rundown

#### Initial Block
The 'initial' block in the upper left is automatically derived from the blog's title, using the first letter therein. It simply links back to the index of the blog.

#### Cover Images for the Blog
The cover images can be changed by droppping new images in the assets/images directory called 'cover.jpg' and 'cover_blur.jpg' respectively.

#### Cover Images for Posts
Adding a cover image to a post is as simple as creating an image in your markup with an alt tag of COVER_IMAGE

`![COVER_IMAGE]`

...and uploading an image to that placeholder location from within Ghost.

All other photos in the post are treated as regular photos.

#### External Resources / Static Pages
For now, linking to pages and external resources is done in the footer, which is located in the partials directroy.

`partials/blog_footer.hbs'

Links can be added and changed there.

#### Disqus support
Within post.hbs, at the bottom is a section that can be uncommented and filled in to provide disqus functionality to your posts.

Make sure to fill in your disqus website shortname.

### Screenshot

![screenshot](https://raw.githubusercontent.com/readypress/mtheme/master/screenshot.png)


mtheme's cover images courtesy GH Cheng (http://www.flickr.com/photos/ghcheng/) from creative commons licenced photos.