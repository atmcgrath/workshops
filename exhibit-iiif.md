---
title: Exhibit.so and IIIF
date: June 24, 2025
author: Alice McGrath
subtitle: ILiADS
format: 
    revealjs:
        theme: moon
        controls: true
        #embed-resources: true
css: "https://alicemcgrath.digital.brynmawr.edu/pres/a3.css"
editor:
    render-on-save: true
---

# Exhibit.so

1. What is it?
2. Understanding IIIF
3. Finding IIIF resources
4. How to use Exhibit.so

# Introduction
[Exhibit.so](https://www.exhibit.so/)

## Examples
- Lily Petteway (BMC 25), [Anchoresses in Medieval Manuscripts](https://www.exhibit.so/exhibits/swG7Rldlar6FXm6YKH3Z)
- Chloe Sun (BMC 27)[Scrapbooking Bryn Mawr: A 1910s Snapshot](https://www.exhibit.so/exhibits/CX5GjKlnLnZR4BasVMdN)

## Why it's great
- Easy to get started
- Browser-based; no sign-in required
- Includes metadata alongside visually-striking content

## Challenges
- Images have to be published on the web
- ...using [IIIF specifications](https://iiif.io/)

## Understanding IIIF

- International Image Interoperability Framework 
- APIs for publishing reusable images
- Zoomable viewers, such as [Mirador](https://projectmirador.org/demo/)
- Change color! Rotate images!
- Images, books, video, and more!

## How it works

- Image API:
  - Image derivatives are "tiled" so deep zoom is possible
  - URLs are structured in a recognizable way
- Presentation API: 
  - Metadata is packaged alongside images
  - Include multiple images for one object (book)
- Manifest: [see example](https://figgy.princeton.edu/concern/scanned_resources/385172c0-43c1-4277-85f7-ea3f1fdffc5d/manifest?manifest=https://figgy.princeton.edu/concern/scanned_resources/385172c0-43c1-4277-85f7-ea3f1fdffc5d/manifest)
  - A json file (JavaScript Object Notation) that includes unique IDs and links to images


## Finding IIIF Resources

- Searching for manifest links!
- To get started: [Guides to finding IIIF resources](https://iiif.io/guides/finding_resources/)
- Collection-specific guidelines are not always up-to-date
- Example: Library of Congress, [Topographical Map of Ocean Co., New Jersey](https://www.loc.gov/item/2012592356/)

## Building your Exhibit.so
- Navigate to [www.exhibit.so](https://www.exhibit.so/)
- Save your Exhibit URL somewhere safe!
- Add resources via IIIF manifest urls
- Add slides for each resource and include text

## Resources
- IIIF Online Training [https://training.iiif.io/iiif-online-workshop/]
- [Canopy](https://canopy-iiif.github.io/docs/) - tool for publishing IIIF collection
- [Exhibit.so self-hosting documentation](https://www.exhibit.so/docs/self-hosting)