# Image Resize Original

Utility module to resize original images previously uploaded to your site.

## The problem

Sites with lots of images, like image galleries, which are around for quite
a while might experience disk space problems.

Nowadays photos are usually uploaded directly from smartphones, but those
got a lot more capable in the past decade. The higher image resolutions
cause bigger file sizes. And if there are lots of those high resolution
photos, they slowly eat up lots of disk space.

If such resolutions aren't ever displayed on your site, anyway - because
you're using smaller image derivatives (image styles) for display - this is
just wasted space.
You can and should set maximum dimensions for fields in image field settings,
but that only applies to newly uploaded files.

So far, there was no way to resize previously uploaded images retrospectively.

Well - now there is.

### When this module's useful

If you have thousands of existing images, resolutions of 6000x4000px or
more, each of those images with file sizes of 8MB or more, this sums up.
Resizing the originals can free several GB of space.

### When this module won't help

If the main disk space hogs are videos or documents (like PDF), resizing
some images won't free much space.

If you actually need those high resolutions, for example for purchased
downloads, then better don't use this module, as it will resize all huge
images from managed files.

## Installation

Install this module using the official 
  [Backdrop CMS instructions](https://docs.backdropcms.org/documentation/extend-with-modules)

## Dependencies

- image (core)

## Issues

Bugs and Feature requests should be reported in the 
 [Issue Queue](https://github.com/backdrop-contrib/image_resizeorig/issues)

## Current Maintainers

- [Indigoxela](https://github.com/indigoxela)

## License

This project is GPLv3 software. See the LICENSE.txt file in this directory for complete text.
