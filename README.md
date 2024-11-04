# Eclipse Memory Analyzer Website

This repository contains the content for the *website* of the Eclipse Memory Analyzer: https://eclipse.dev/mat/

If you are looking for the code repository of Eclipse Memory Analyzer, it is hosted on the Eclipse git infrastructure and you can view it [here](https://github.com/eclipse-mat/mat). See the [developers](https://eclipse.dev/mat/developers/) section of the website for more details.
This boilerplate was created to help Eclipse Projects migrate their website to Hugo!

The website is bult with Hugo and uses the [Hugo Solstice Theme](https://gitlab.eclipse.org/eclipsefdn/it/webdev/hugo-solstice-theme) by the Eclipse Foundation.

[[_TOC_]]

## Getting started

Clone the project with submodules and start a local web server:

```bash
git clone --recurse-submodules https://github.com/eclipse-mat/website.git
cd website
hugo server
```

### Update hugo-solstice-theme

The [hugo-solstice-theme](https://gitlab.eclipse.org/eclipsefdn/it/webdev/hugo-solstice-theme) was added to this project as a Git submodule. You can update to the latest version before getting started:

```bash
git submodule update --remote
```

Please make sure to keep this sub-module up-to-date if you decide to utilize it. The Eclipse Foundation Webdev team regularly publishes new versions. For more information, please see Git documentation on [submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

## Build Memory Analyzer project's website

The MAT websites is built with [Hugo](https://gohugo.io/).

To build it, simple call
```bash
hugo
```
in the website project root. This will generate the static content under the ```/public``` directlry. Note that Hugo does not "clean" the public directory before builds by default.

To see the results locally, start 
```bash
hugo server
```

The pages are automatically updated as you edit/save them.

## Learning Resources

* Hugo [documentation](https://gohugo.io/documentation/) 
* Hugo Solstice [Theme] (https://gitlab.eclipse.org/eclipsefdn/it/webdev/hugo-solstice-theme)

## Contributing

1. [Fork](https://docs.gitlab.com/ee/user/project/repository/forking_workflow.html) the [website](https://github.com/eclipse-mat/website.git) repository
2. Clone repository the forked repository
3. Create your feature branch: `git checkout -b my-new-feature`
4. Commit your changes: `git commit -m 'Add some feature' -s`
5. Push feature branch: `git push origin my-new-feature`
6. Submit a pull request

### Declared Project Licenses

This program and the accompanying materials are made available under the terms
of the Eclipse Public License v. 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0.

SPDX-License-Identifier: EPL-2.0

## Related projects

### [solstice-assets](https://gitlab.eclipse.org/eclipsefdn/it/webdev/solstice-assets)

Images, less and JavaScript files for the Eclipse Foundation look and feel.

### [hugo-solstice-theme](https://gitlab.eclipse.org/eclipsefdn/it/webdev/hugo-solstice-theme)

Hugo theme of the Eclipse Foundation look and feel.

## Bugs and feature requests

Have a bug or a feature request? Please search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/eclipse-mat/website/issues/new).

## Trademarks

* Eclipse® is a Trademark of the Eclipse Foundation, Inc.
* Eclipse Foundation is a Trademark of the Eclipse Foundation, Inc.

## Copyright and license

Released under the [Eclipse Public License Version 2.0 (EPL-2.0)](LICENSE).
