# Journal

## 09242019

Initial entry.

Finally came-up with a name for this project last night.  Instead of trying to incorporate all of the current and proposed features of [JSFS](https://github.com/jjg/jsfs/) along with all of [RESTduino](https://github.com/jjg/restduino), and a single "firmware" to [span microcontrollers to mainframes](https://jasongullickson.com/posts/has-it-all-been-leading-to-this/), I'm going to focus on delivering an initial version targeting [MicroPython](https://micropython.org/) devices.  This will change (although I'm not sure if that will be an expansion of this initial version, or perhaps different "flavors"), but I really want to make sure I can deliver a quality experience on MicroPython devices since the whole motivation behind pursuing this is to create a platform on which to develop privacy-respecting "smart" devices (another project in need of a name...).

I've been dabbling with this and have some initial code I need to move out of [halfbaked](https://gitlab.com/jgullickson/halfbaked) and into this repository.  Nothing that "works" quite yet, but this time I'm trying to keep track of incremental progress instead of focusing on only checking-in stuff that works.

I'm also using this as an opportunity to test-drive [codeberg](https://codeberg.org).  After my experience with Github and Gitlab I'm hesitant to invest too much time in working with anything other than raw, self-hosted git repositories, but this project could use some of the project management features codeberg provides, and if I have any intention of collaborating with others, it's going to be less of a hurdle for others.

To that end there's a few things I'd like to include at the beginning of this project.  The first is that I want to make sure I set the repository (and my own workflow) up to accommodate pull requests.  I'm using [this post](https://gist.github.com/Chaser324/ce0505fbed06b947d962) for reference so hopefully that's the way it's done.

What's not crystal-clear to me from the linked post is if there is a role for things like `develop` branches.  I've been working (involuntarily) with [gitflow](https://nvie.com/posts/a-successful-git-branching-model/) for so long that it feels spooky to have nothing more than `master` and feature branches, but maybe that's all you need...?

The second is that I'd like to have some sort of code of conduct in place.  First and foremost I want something enforceable but ideally doesn't require too much policing (if you know me you know how I feel about police).  I haven't seen an existing CoC that I'm ready to adopt wholesale, but I'd also like to avoid creating something bespoke (I'm certainly no expert in this area and I'd like to avoid making mistakes others have corrected) so for now I'm on the lookout for something appropriate.


## 10012019

Decided to rename the project to RESTMetal to avoid confusion with Apple's unrelated [WebMetal](https://en.wikipedia.org/wiki/WebGPU) project.

Had a realization this morning that RESTMetal unblocks one of the barriers I ran into in another project [NextBook](https://codeberg.org/jjg/nextbook).  I'll leave documenting the details to the other project but it's exciting to already have another application for this project already.
