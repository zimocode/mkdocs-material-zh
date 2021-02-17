---
template: overrides/main.html
---

# <span hidden>Insiders</span> :logo: :material-plus: :octicons-heart-fill-24:{: .tx-heart }

Material for MkDocs uses the _sponsorware_ release strategy, which means
that _new features are first exclusively released to sponsors_ as part of
__Insiders__. Read on to learn [how sponsorship works][1], and how easy it is
to [get access to Insiders][2].

<figure class="tx-video" markdown="1">
  <div class="tx-video__inner">
    <iframe src="https://streamable.com/e/zmtb00" allowfullscreen></iframe>
  </div>
  <figcaption markdown="1">

A demo is worth a thousand words — check it out at
[squidfunk.github.io/mkdocs-material-insiders][3]

  </figcaption>
</figure>

  [1]: #how-sponsorship-works
  [2]: #how-to-become-a-sponsor
  [3]: https://squidfunk.github.io/mkdocs-material-insiders/

## How sponsorship works

New features first land in Insiders, which means that _sponsors will have access
immediately_. Every feature is tied to a funding goal in monthly subscriptions.
When a funding goal is hit, the features that are tied to it are merged back
into Material for MkDocs and released for general availability. Bugfixes are
always released simultaneously in both editions.[^1]

  [^1]:
    You may ask yourself why you should pay for something that is Open Source.
    Doesn't that contradict the ethos of Open Source software? Yes and no. Yes,
    some features are locked behind a monthly subscription, which means they are
    only accessible when paying a small amount of money. No, the features are
    only exclusive for a short time until specific funding goals are hit. Making
    an Open Source project sustainable is exceptionally hard: maintainers burn
    out, projects are abandoned. That's not great and very unpredictable. The
    sponsorware model ensures that if you decide to use Material for MkDocs,
    you can be sure that bugs are fixed quickly and new features are added
    regularly.

_Don't want to sponsor? No problem, Material for MkDocs already has tons of
features available, so chances are that most of your requirements are already
satisfied. See the [list of exclusive features][4] to learn which features are
currently only available to sponsors._

  [4]: #exclusive-features

## How to become a sponsor

You can become a sponsor using your individual or organization's GitHub account.
Just visit __[squidfunk's sponsor profile][5]__, pick any tier __from
$10/month__, and complete the checkout. Then, after a few hours, @squidfunk will
add you as a collaborator to the super-secret private GitHub repositority
containing the Insiders edition, which contains all [brand new and exclusive
features][4].

__Important__: If you're sponsoring @squidfunk through a GitHub organization,
please send a short email to sponsors@squidfunk.com with the name of your
organization and the account that should be added as a collaborator.[^2]

  [^2]:
    It's currently not possible to grant access to each member of an
    organization, as GitHub only allows for adding users. Thus, after
    sponsoring, please send an email to sponsors@squidfunk.com, stating which
    account should become a collaborator of the Insiders repository. We're
    working on a solution which will make access to organizations much simpler.
    To ensure that access is not tied to a particular individual GitHub account,
    create a bot account (i.e. a GitHub account that is not tied to a specific
    individual), and use this account for the sponsoring. After being added to
    the list of collaborators, the bot account can create a private fork of the
    private Insiders GitHub repository, and grant access to all members of the
    organizations.

You can cancel your sponsorship anytime.[^3]

  [^3]:
    If you cancel your sponsorship, GitHub schedules a cancellation request
    which will become effective at the end of the billing cycle, which ends at
    the 22nd of a month for monthly sponsorships. This means that even though
    you cancel your sponsorship, you will keep your access to Insiders as long
    as your cancellation isn't effective. All charges are processed by GitHub
    through Stripe. As we don't receive any information regarding your payment,
    and GitHub doesn't offer refunds, sponsorships are non-refundable.

[:octicons-heart-fill-24:{: .tx-heart } &nbsp; Join our <span class="tx-insiders-count"></span> awesome sponsors][5]{: .md-button .md-button--primary .tx-insiders-button }

<div class="tx-insiders-container" markdown="1" hidden>
  <div class="tx-insiders-list"></div>
  _If you sponsor publicly, you're automatically added here with a link to
  your profile and avatar to show your support for Material for MkDocs.
  Alternatively, if you wish to keep your sponsorship private, you'll be a 
  silent +1. You can select visibility during checkout and change it 
  afterwards._
</div>

<script>
  fetch("https://gpiqp43wvb.execute-api.us-east-1.amazonaws.com/_/").then(function(e){return e.json()}).then(function(e){var t=document.querySelector(".tx-insiders-list"),n=0;for(var o of e.sponsors)if("PUBLIC"===o.type){var s;(s=document.createElement("a")).href=o.url,s.title="@"+o.name,s.className="tx-insiders-list__item",t.appendChild(s);var r=document.createElement("img");r.src=o.image,s.appendChild(r)}else n++;(s=document.createElement("a")).href="https://github.com/sponsors/squidfunk",s.title="[private]",s.innerText="+"+n,s.className="tx-insiders-list__item tx-insiders-list__item--private",t.appendChild(s),document.querySelector(".tx-insiders-count").innerText=e.sponsors.length,document.querySelector(".tx-insiders-container").removeAttribute("hidden"),document.querySelector('.tx-insiders-total').innerText=" $ "+e.total.toString().replace(/(\d)(?=(\d{3})+(?!\d))/g, "$1,")}).catch(console.log);
</script>

  [5]: https://github.com/sponsors/squidfunk

## Exclusive features

The following features are currently exclusively available to sponsors:

<div class="tx-columns" markdown="1">

- [x] [Section index pages :material-new-box:][21]
- [x] [Latest release tag][15]
- [x] [Color palette toggle][16]
- [x] [Versioning][14]
- [x] [Site language selection][13]
- [x] [Sticky navigation tabs][20]
- [x] [Native Mermaid.js integration][23]
- [x] [Admonition inline blocks][12]
- [x] [Search suggestions][17]
- [x] [Search highlighting][18]
- [x] [Search sharing][19]
- [x] [Remove generator notice][22]

</div>

_New features are added to this list every few weeks, so be sure to come back
from time to time to learn about what's new, or follow [@squidfunk on 
:fontawesome-brands-twitter:{: .twitter } Twitter][6] to stay updated._

  [6]: https://twitter.com/squidfunk

## Funding<span class="tx-insiders-total tx-insiders-count"></span>

### Goals

Following is a list of funding goals. When a funding goal is hit, the features
that are tied to it are merged back into Material for MkDocs and released to
the public for general availability.

#### $ 1,500 – Bhut Jolokia

- [x] [Admonition inline blocks][12]
- [x] [Site language selection][13]
- [x] [Versioning][14]

  [12]: reference/admonitions.md#inline-blocks
  [13]: setup/changing-the-language.md#site-language-selector
  [14]: setup/setting-up-versioning.md#versioning

#### $ 2,000 – Black Pearl

- [x] [Latest release tag][15]
- [x] [Color palette toggle][16]
- [ ] Code block palette toggle

  [15]: setup/adding-a-git-repository.md#latest-release
  [16]: setup/changing-the-colors.md#color-palette-toggle

#### $ 2,500 – Biquinho Vermelho

- [x] [Search suggestions][17]
- [x] [Search highlighting][18]
- [x] [Search sharing][19]

  [17]: setup/setting-up-site-search.md#search-suggestions
  [18]: setup/setting-up-site-search.md#search-highlighting
  [19]: setup/setting-up-site-search.md#search-sharing

#### $ 3,000 – Caribbean Red

- [x] [Sticky navigation tabs][20]
- [x] [Section index pages][21]
- [x] [Remove generator notice][22]

  [20]: setup/setting-up-navigation.md#sticky-navigation-tabs
  [21]: setup/setting-up-navigation.md#section-index-pages
  [22]: setup/setting-up-the-footer.md#remove-generator


#### $ 5,000 – Aji Panca

- [x] [Native Mermaid.js integration][23]

  [23]: reference/diagrams.md

#### Future

- [ ] [Material for MkDocs Live Edit][24]
- [ ] Improved search result summaries
- [ ] List of last searches
- [ ] Table of contents follows active anchor
- [ ] Table of contents auto-collapse
- [ ] Table of contents shows which sections have search results
- [ ] Native lightbox for (inline) images
- [ ] New layouts and styles (e.g. vertical)
- [ ] ... and much more ...

  [24]: https://twitter.com/squidfunk/status/1338252230265360391

### Goals completed

#### $ 500 – Madame Jeanette

- [x] Improved search result grouping
- [x] Improved search result relevance and scoring
- [x] Missing query terms in search results

#### $ 1,000 – Prairie Fire

- [x] [Navigation sections][7]
- [x] [Navigation expansion][8]
- [x] [Hiding the sidebars][9]
- [x] [Table of contents in navigation][10]
- [x] [Header hides on scroll][11]

  [7]: setup/setting-up-navigation.md#navigation-sections
  [8]: setup/setting-up-navigation.md#navigation-expansion
  [9]: setup/setting-up-navigation.md#hide-the-sidebars
  [10]: setup/setting-up-navigation.md#navigation-integration
  [11]: setup/setting-up-the-header.md#automatic-hiding

## Frequently asked questions

### Compatibility

_We're running an open source project and want to make sure that users can build
the documentation without having access to Insiders. Is this still possible?_

Yes. Insiders is compatible with Material for MkDocs. All new features are
implemented behind feature flags; all configuration changes are 
backward-compatible. This means that your users will be able to build the
documentation locally with Material for MkDocs and when they push their changes,
it can be built with Insiders (e.g. as part of GitHub Actions). Thus, it's
recommended to [install Insiders][25] only in CI, as you don't want to expose
your `GH_TOKEN` to users.

  [25]: publishing-your-site.md#github-pages

### Terms

_We're using Material for MkDocs to build the developer documentation of a
commercial project. Can we use Insiders under the same terms and conditions?_

Yes. Whether you're an individual or a company, you may use _Material for MkDocs
Insiders_ precisely under the same terms as Material for MkDocs, which are given
by the [MIT license][26]. However, we kindly ask you to respect the following
guidelines:

- Please __don't distribute the source code__ of Insiders. You may freely use
  it for public, private or commercial projects, fork it, mirror it, do whatever
  you want with it, but please don't release the source code, as it would
  counteract the sponsorware strategy.

- If you cancel your subscription, you're removed as a collaborator and will
  miss out on future updates of Insiders. However, you may __use the latest
  version__ that's available to you __as long as you like__. Just remember that
  [GitHub deletes private forks][27].

  [26]: license.md
  [27]: https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/removing-a-collaborator-from-a-personal-repository
