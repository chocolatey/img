# Chocolatey Images

This repository holds all images that can be found on Chocolatey websites.

This site is hosted on GitHub Pages at `https://img.chocolatey.org/` + `path/to/image.png`.

## Adding Images to This Repository

Keep the following in mind when adding new images:

* Try to avoid adding new folders. A lot of categories have already been created. Only create a new folder if no other existing option makes sense for a category.
* Size images properly. Do not add images that are too much larger than what is actually needed.

## Where to Find Stock Images

**Using images from Google should be avoided**. These images are copyrighted and are not recommended for commercial use. There are a number of websites that offer royalty free usage of images:

* https://gratisography.com/
* https://pixabay.com/
* https://unsplash.com/
* https://morguefile.com/

## Using Images in Source Code

Most of the time, it is preferred to define an image as below:

HTML:

```html
<img src="https://img.chocolatey.org/path/to/image.png" alt="Context about image" />
```

Markdown or MDX:

```md
![Context about image](https://img.chocolatey.org/path/to/image.png)
```

To add spacing around an image:

```html
<img class="mb-3" src="https://img.chocolatey.org/path/to/image.png" alt="Context about image" />

/* CSS Class Usage */
.mb-3 /* Adds spacing to bottom */
.mt-3 /* Adds spacing to top */
.ms-3 /* Adds spacing to left */
.me-3 /* Adds spacing to right */
```

To remove the border around an image:

```html
<img class="border-0" src="https://img.chocolatey.org/path/to/image.png" alt="Context about image" />
```

For a centered image:

```html
<div class="text-center"><img src="https://img.chocolatey.org/path/to/image.png" alt="Context about image" /></div>
```

For a left aligned image (with text wrapping):

```html
<img class="float-start me-3" src="https://img.chocolatey.org/path/to/image.png" alt="Context about image" width="400" />

/* The defined width could be anything 600 and below, as long as it doesn't exceed the image properties */
```

For a right aligned image (with text wrapping):

```html
<img class="float-end ms-3" src="https://img.chocolatey.org/path/to/image.png" alt="Context about image" width="400"/>

/* The defined width could be anything 600 and below, as long as it doesn't exceed the image properties */
```
