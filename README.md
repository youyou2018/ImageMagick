[![Build Status](https://travis-ci.org/ImageMagick/ImageMagick.svg?branch=master)](https://travis-ci.org/ImageMagick/ImageMagick)

#Introduction to ImageMagick

  ImageMagick® is a software suite to create, edit, compose, or convert
  bitmap images. It can read and write images in a variety of formats (over
  200) including PNG, JPEG, JPEG-2000, GIF, TIFF, DPX, EXR, WebP, Postscript,
  PDF, and SVG.  Use ImageMagick to resize, flip, mirror, rotate, distort,
  shear and transform images, adjust image colors, apply various special
  effects, or draw text, lines, polygons, ellipses and Bézier curves.
  
  The functionality of ImageMagick is typically utilized from the command
  line or you can use the features from programs written in your favorite
  programming language. Choose from these interfaces: G2F (Ada), MagickCore
  (C), MagickWand (C), ChMagick (Ch), ImageMagickObject (COM+), Magick++
  (C++), JMagick (Java), L-Magick (Lisp), NMagick (Neko/haXe), MagickNet
  (.NET), PascalMagick (Pascal), PerlMagick (Perl), MagickWand for PHP
  (PHP), IMagick (PHP), PythonMagick (Python), RMagick (Ruby), or TclMagick
  (Tcl/TK). With a language interface, use ImageMagick to modify or create
  images dynamically and automagically.

  ImageMagick utilizes multiple computational threads to increase performance
  and can read, process, or write mega-, giga-, or tera-pixel image sizes.
  
  ImageMagick is free software delivered as a ready-to-run binary distribution
  or as source code that you may freely use, copy, modify, and distribute
  in both open and proprietary applications. It is distributed under the
  Apache 2.0 license, approved by the OSI and recommended for use by the OSSCC.
  
  The ImageMagick development process ensures a stable API and ABI. Before
  each ImageMagick release, we perform a comprehensive security assessment
  that includes memory and thread error detection to prevent security
  vulnerabilities.

  ImageMagick is available from http://www.imagemagick.org/download to
  download. It runs on Linux, Windows, Mac Os X, iOS, Android OS, and others.

  The authoritative ImageMagick web site is http://www.imagemagick.org.


#Features and Capabilities
  
  Here are just a few examples of what ImageMagick can do:
  
      * Format conversion: convert an image from one format to another (e.g.
        PNG to JPEG).
      * Transform: resize, rotate, crop, flip or trim an image.
      * Transparency: render portions of an image invisible.
      * Draw: add shapes or text to an image.
      * Decorate: add a border or frame to an image.
      * Special effects: blur, sharpen, threshold, or tint an image.
      * Animation: create a GIF animation sequence from a group of images.
      * Text & comments: insert descriptive or artistic text in an image.
      * Image identification: describe the format and attributes of an image.
      * Composite: overlap one image over another.
      * Montage: juxtapose image thumbnails on an image canvas.
      * Generalized pixel distortion: correct for, or induce image distortions
        including perspective.
      * Computer vision: Canny edge detection.
      * Morphology of shapes: extract features, describe shapes and recognize
        patterns in images.
      * Motion picture support: read and write the common image formats used in
        digital film work.
      * Image calculator: apply a mathematical expression to an image or image
        channels.
      * Connected component labeling: uniquely label connected regions in an
        image.
      * Discrete Fourier transform: implements the forward and inverse DFT.
      * Perceptual hash: maps visually identical images to the same or similar
        hash-- useful in image retrieval, authentication, indexing, or copy
        detection as well as digital watermarking.
      * Color management: accurate color management with color profiles or in
        lieu of-- built-in gamma compression or expansion as demanded by the
        colorspace.
      * High dynamic-range images: accurately represent the wide range of
        intensity levels found in real scenes ranging from the brightest direct
        sunlight to the deepest darkest shadows.
      * Encipher or decipher an image: convert ordinary images into
        unintelligible gibberish and back again.
      * Virtual pixel support: convenient access to pixels outside the image
        region.
      * Large image support: read, process, or write mega-, giga-, or
        tera-pixel image sizes.
      * Threads of execution support: ImageMagick is thread safe and most
        internal algorithms are OpenMP-enabled to take advantage of speed-ups
        offered by multicore processor chips.
      * Distributed pixel cache: offload intermediate pixel storage to one or
        more remote servers.
      * Heterogeneous distributed processing: certain algorithms are
        OpenCL-enabled to take advantage of speed-ups offered by executing in
        concert across heterogeneous platforms consisting of CPUs, GPUs, and
        other processors.
      * ImageMagick on the iPhone: convert, edit, or compose images on your
        iPhone.
  
  Examples of ImageMagick Usage, http://www.imagemagick.org/Usage/, shows how
  to use ImageMagick from the command-line to accomplish any of these tasks and
  much more. Also, see Fred's ImageMagick Scripts,
  http://www.fmwconcepts.com/imagemagick/: a plethora of command-line scripts
  that perform geometric transforms, blurs, sharpens, edging, noise removal,
  and color manipulations.
