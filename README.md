[Whistlepost]: https://www.whistlepost.org
[Schema.org]: https://www.schema.org
[Forestry.io]: https://www.forestry.io

# Whistlepost Content Template

This repository provides the default template for Whistlepost site content.

## Overview

[Whistlepost] is a _content-first_ Web publishing platform that provides true separation of content and presentation
for websites. Often we can allow visual layout and design to distract from site content and structure. Whistlepost
is designed to provide clear separation between the content and visual aspects of Web development.

### Schema.org

[Schema.org] is a collaboration of many organizations to define a common semantic meaning for content published 
on the Web (also known as the _Semantic Web_). This repository provides a default structure for Whistlepost content
based on Schema.org entities. It includes Front Matter and settings for integration with [Forestry.io] for creation
and management of content.

### Forestry.io

[Forestry.io] is an online CMS designed for static site generators (SSGs) such as Hugo and Jekyll. However, it is
versatile enough to support JSON-based content also such as is used in Whistlepost. The Front Matter provided in
this repository makes it easy to start creating content right away with predefined form-based content types based
on Schema.org entities.


## Getting started

To start creating your new Whistlepost site you first need to create a content repository. You can do this easily
on Github by using this repository as a template for your new repository. Other Git-based tools may also be used
to fork this repository.

### Repository structure

The following file structure is included in this template:

* assets - contains static site content, typically images and other media uploaded via Forestry.io 
* content - contains the site structure and content
* build.gradle - build script for packaging the content as a deployable bundle
* docker-compose.yml - Docker configuration for local testing of site content
* Makefile - common goals for local development

### Importing to Forestry.io

To manage content with Forestry.io you need to create a new site and link it to your content repository. Once
linked you should see the site structure replicated in the dashboard and you can start creating new content right
away.
