# ![WICG Logo](https://avatars1.githubusercontent.com/u/13145324?s=100)

# Welcome to the WICG Proposals Repo!

This is the WICG proposals repo, a place for well-formed ideas to start their incubation
journey. Plan to use this repo's [issue tracker](https://github.com/WICG/proposals/issues)
for submitting and discussing new proposals much like
[Discourse threads](https://discourse.wicg.io/) were used previously. Discourse will remain
a good home for less well-formed ideas to germinate, for early explorations, and for other
discussions. But if you have a well-formed idea, you may skip Discourse and start an issue
here. Think of Discourse as the potential destination for earlier, less-well-formed concepts,
and this repo's issue tracker for more crystalized proposals.

Please note that all proposals in this repo (including those in separate markdown documents)
have no official status in the WICG as incubations.

## Evolving from Discourse

Previously, we used [Discourse discussions](https://discourse.wicg.io/) for anything that 
wasn't an official incubation (i.e., an incubation with its own repo). That forum was host
to all discussions, early explorations, suggestions, and proposals for the web platform. 
The goal was to help establish our community where those who participated in developing 
web standards and those who didn't have the time but still wanted to influence/advance the
web could mingle and share ideas. In short, bringing together the broadest possible 
community of interested developers to give and receive feedback. Our goal was largely 
successful.

As time passed, the developer ecosystem shifted. We now see that GitHub has a larger 
community of web developer interest than ever before, is the primary host of specification
development for major web standards organizations and has great tools and integration for
project and issue management. We also see an opportunity to provide more direct guidance
on how to start an incubation, by creating this dedicated home for future incubations to
be proposed that is distinct from other ideas, explorations, and discussions about the web 
platform.

This proposals repo will meet these changing needs. Here in GitHub you can easily extend your
existing repo and issue monitoring techniques to keep track of what's being proposed.
Additionally, this gives us a chance to clarify the WICG process for starting new incubations:
rather than ask that proposals for new incubations be started on Discourse (intermingled with
all other Discourse conversations), instead well-formed ideas should be filed as issues here in
this repo, making it clear that these proposal issues intend to begin life as an incubation.
Our expectations for evaluation of new proposals remains the same: as soon as sufficient interest
is shown in the proposal's issue thread (notably from potential implementers), the WICG chairs
will enable a team of editors to manage the proposal, and those team members can begin work in
a new repo or move ownership of an existing GitHub repo to WICG. For more information about the
evaluation and incubation process, see
[the admin repo's README file](https://github.com/WICG/admin/blob/gh-pages/README.md).

We continue to recommend that our community participate in Discourse for less well-formed ideas
to germinate, for early explorations, and for other discussions. As these ideas, explorations,
and discussions mature, they may form into a proposal which should then be filed as an issue in
this repo.

## What does a proposal look like?

A proposal outlines a particular problem or challenge on the web and offers a potential concrete
solution. Without being too prescriptive, you know you've got a proposal when you can articulate
a specific way (procedurally, algorithmically, declaratively) that a new or current web technology
solves an existing problem or challenge. If the problem is unclear, or the potential solution is
too abstract you're not quite there yet.

For example, this is not a proposal:

> "Websites have lots of bugs because they don't get updated or because browsers change their 
> behavior over time. There should be a universal way for users to report bugs to websites so that 
> they get fixed."

Instead, a proposal might be:

> "Websites have lots of bugs because they don't get updated or because browsers change their 
> behavior over time. One way to solve this is to create an experience in the browser that allows
> users to record a set of steps that reproduce the problem, and then standardize the format for
> these replay instructions, and provide an API to allow sites to capture this feedback or an HTTP
> header to post this feedback back to their site. Below I describe the proposed format and API...
> `<snip>`" 

## Proposals in issues vs. separate markdown documents?

If you would like to make a proposal as a separate markdown document (if for example, it was
developed in a separate repo) you are welcome to link to it from the proposal issue; just provide
a bit of high-level context on the problem and proposed solution in the issue as well.
Alternatively, if you'd like to use the proposal repository itself to host a separate markdown
document, you are welcome to submit a PR for it— we still ask that you file an issue to track
your proposal and provide context as previously mentioned. This will make it easier for our entire
community to use the issue tracker to search through all proposals.

## Getting Started

Is your proposal unique? Head over to the [issues list](https://github.com/WICG/proposals/issues)
and search for it; if it was suggested by someone else give it your support with a 👍 or leave a
comment. If you don't find anything there, consider starting a new issue. (You are also welcome
to visit [Discourse](https://discourse.wicg.io/) and search there as well, especially while this
repo is first getting populated). 

## Search proposals by category

The proposals are grouped by category (as discussions are on Discourse):

| Label | Short description | Discourse category |
|-------|-------------------|--------------------|
| **[APIs](https://github.com/WICG/proposals/labels/Category%3A%20APIs)** | All proposals about JS APIs. | [APIs](https://discourse.wicg.io/c/apis/6) |
| **[HTML](https://github.com/WICG/proposals/labels/Category%3A%20HTML)** | HTML-related proposals (not only the HTML standard but any markup-related ideas). | [HTML](https://discourse.wicg.io/c/html/10) |
| **[CSS](https://github.com/WICG/proposals/labels/Category%3A%20CSS)** | CSS-related proposals. | [CSS](https://discourse.wicg.io/c/css/8) |
| **[Uncategorized](https://github.com/WICG/proposals/labels/Category%3A%20Uncategorized)** | Proposals that don't fit into any other existing category. | [Uncategorized](https://discourse.wicg.io/c/uncategorized/1) |
| **[Meta](https://github.com/WICG/proposals/labels/Category%3A%20meta)** | Proposals/ideas/discussions about this proposals repo, its organization, how it works, and how we can improve it. | [meta](https://discourse.wicg.io/c/meta/3) |   
| **[JS](https://github.com/WICG/proposals/labels/Category%3A%20JS)** | JS language proposals. | [JS](https://discourse.wicg.io/c/js/18) |
| **[Security](https://github.com/WICG/proposals/labels/Category%3A%20Security)** | Proposals with a focus on web security, client-side protections, improved site security, etc. | [Security](https://discourse.wicg.io/c/security/21) |
| **[Protocols](https://github.com/WICG/proposals/labels/Category%3A%20protocols)** | Proposals for anything relating to protocols such as HTTP, Web Sockets, & JSON-based protocols. | [protocols](https://discourse.wicg.io/c/protocols/14) |
| **[WASM](https://github.com/WICG/proposals/labels/Category%3A%20WASM)** | Proposals for the WebAssembly language. Also consider reviewing [the WebAssembly Community Group's issue tracker](https://github.com/webassembly/spec/issues). | [asm.js](https://discourse.wicg.io/c/asm-js/16) |
| **[Architecture](https://github.com/WICG/proposals/labels/Category%3A%20Architecture)** | For proposals related to web architecture or architectural components. | [Architecture](https://discourse.wicg.io/c/architecture/13) |
| **[Media & RTC](https://github.com/WICG/proposals/labels/Category%3A%20Media%20%26%20RTC)** | For Media (video/audio) and Real-Time Communications proposals. | [Media and Real-Time Communications](https://discourse.wicg.io/c/mediartc/20) |
| **[Web Components](https://github.com/WICG/proposals/labels/Category%3A%20Web%20Components)** | Proposals for web components. Also consider reviewing [the webcomponents incubation issue tracker](https://github.com/w3c/webcomponents/issues) | [Web Components](https://discourse.wicg.io/c/web-components/9) |

To help bridge Discourse discussions with those happening in this repo, we plan to setup an automated
system to notify the Discourse community when new proposals are started in this repo.

