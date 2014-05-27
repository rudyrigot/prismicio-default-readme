## LANGUAGE development kit for prismic.io

### Getting started

#### Install the kit for your project

This kit gets installed like any LANGUAGE library.

*(Feel free to detail the proper steps for beginners by [submitting a pull request](https://developers.prismic.io/documentation/UszOeAEAANUlwFpp/contribute-to-the-official-kits).)*

#### Get started with prismic.io

You can find out [how to get started with prismic.io](https://developers.prismic.io/documentation/UjBaQsuvzdIHvE4D/getting-started) on our [prismic.io developer's portal](https://developers.prismic.io/).

#### Get started using the kit

Also on our [prismic.io developer's portal](https://developers.prismic.io/), on top of our full documentation, you will:
 * get a thorough introduction of [how to use prismic.io kits](https://developers.prismic.io/documentation/UjBe8bGIJ3EKtgBZ/api-documentation#kits-and-helpers), including this one.
 * see [what else is available for LANGUAGE](https://developers.prismic.io): starter projects, examples, ...

### Using the kit

#### Kit's detailed documentation

You can find the documentation of the LANGUAGE kit as comments within the kit's source code.
 *(Feel free to talk to us about generated docs for LANGUAGE.)*

#### Specific LANGUAGE kit syntax

Thanks to LANGUAGE's syntax, this kit contains some mild differences and syntastic sugar over the section of our documentation that tells you [how to use prismic.io kits](https://developers.prismic.io/documentation/UjBe8bGIJ3EKtgBZ/api-documentation#kits-and-helpers) in general (which you should read first). The differences are listed here:
 * 

Knowing all that, here is typical code written with the Ruby kit:

 * A typical API object instantiation looks like this: `Prismic.api(url, opts)`
 * A typical querying looks like this: `api.form('everything').query('[[:d = at(document.type, "product")]]').ref(ref).submit()`
 * A typical fragment manipulation looks like this: `doc.getImageView('article.image', 'icon').url`
 * A typical fragment serialization to HTML looks like this: `doc.getStructuredText('article.body').asHtml(linkResolver)`

### Changelog

Need to see what changed, or to upgrade your kit? We keep our changelog on [this repository's "Releases" tab]().

### Contribute to the kit

Contribution is open to all developer levels, read our "[Contribute to the official kits](https://developers.prismic.io/documentation/UszOeAEAANUlwFpp/contribute-to-the-official-kits)" documentation to learn more.

#### Install the kit locally

This kit gets installed like any LANGUAGE library.

*(Feel free to detail the proper steps for beginners by [submitting a pull request](https://developers.prismic.io/documentation/UszOeAEAANUlwFpp/contribute-to-the-official-kits).)*

#### Test

Please write tests for any bugfix or new feature.

If you find existing code that is not optimally tested and wish to make it better, we really appreciate it; but you should document it on its own branch and its own pull request.

#### Documentation

Please document any bugfix or new feature.

If you find existing code that is not optimally documented and wish to make it better, we really appreciate it; but you should document it on its own branch and its own pull request.

### Licence

This software is licensed under the Apache 2 license, quoted below.

Copyright 2013 Zengularity (http://www.zengularity.com).

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
