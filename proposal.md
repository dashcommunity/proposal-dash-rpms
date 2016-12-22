# Proposal:<br />Dash Core for Fedora, CentOS, and RHEL

Dash Core software professionally packaged, tested, maintained, and delivered
for the [Fedora](http://fedoraproject.org/), [CentOS](https://www.centos.org/),
and
[RHEL](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux)
linux platforms.

### Overview

This is a request to fund a very modest Dash patronage to help offset some of
effort associated to the development and process of building, packaging,
delivery, and maintenance of Dash Core code for the premier family of linux
operating systems: Red Hat -- Fedora, CentOS and RHEL. I.e., "release
engineering" for this family of operating systems. I have been building packages
for this line of operating systems for approximately 8 months now and will
continue to do so, proposal accepted or not. This is a plea to assist in my
efforts as I improve and *expand* the scope of what I am already doing.

*...more detail...*

A mature software application ideally needs mature packaging for the various
permutations of operating system platforms on which it runs. Examples: for
Ubuntu this means .deb (for apt-get automation), for MacOS this means .pkg, etc.
For the Red Hat linux family of operating systems -- Fedora, CentOS, RHEL --
this means RPM packages (.rpm) and YUM/DNF repositories.

The advantages are that you build these packages consistently and they allow
predictable and easy installation and update for users. Upon installation they
pull in the dependencies they need without the user having to think about them,
and the operating system can track and manage updates cleanly and efficiently.

Aspirationally, there is opportunaty to have Dash Core shipped with the Fedora
operating system by default. More on that later...

Available today: I developed the packaging specs, build and digitally sign
packages and make them available through automated means. I have also written
installation configuration instruction tailered to these builds and these
platforms.

> ***But there is a lot more to be done to really professionalize the
product for this family of operating systems.***

> ***Such packaging and availability would set Dash on par with Bitcoin in the
near term, and establish delivery professionalism certainly ahead of other
crypto-currencies.***

**Who am I?** I am dAgrarian (forums), taw00 (github), t0dd and agrarian (other
places).

### Scope

I build and test on a number of local virtual and VPS instances for both stable
(currently 0.12.0.58) and testnet (0.12.1) Dash Core. This will continue
indefinitely and expand in scope.

##### Deliverables

* Source packages: <https://github.com/taw00/dashcore-srpms>
* Binary packages: <https://keybase.pub/toddwarner/repo/dashcore/>
* General usage instruction: <https://gist.github.com/taw00/b2382aaabb321b0cf9ce104185e1b3b7>
* Tailored testnet masternode guidance: <https://gist.github.com/taw00/e978f862ee1ad66722e16bcc8cf18ca5>
* You can find many of my announcements in the Dash Forums such as [this one](https://www.dash.org/forum/threads/12-1-testnet-testing-phase-two-ignition.10818/page-8#post-108491), [this one](https://www.dash.org/forum/threads/testnet-masternode-guide-for-fedora-centos-rhel.11950/), and [this one](https://www.dash.org/forum/threads/12-1-testnet-testing-phase-two-ignition.10818/page-6#post-106852)<br />*(I don't announce every test build)*
* Three month (end of cycle) status report

##### Aspirationally, I strive to...

* Drive Dash Core into Fedora's formal release process and official repositories.<br />*This would be a not-so-minor coup for the Dash community.*
* Drive the build process into the Dash Core Team's formal release processes
* Expand the set of packages beyond core, for example, the Electrum wallet, Sentinel, etc.
* Make Dash Core [SELinux-friendly](https://en.wikipedia.org/wiki/Security-Enhanced_Linux) (security enhanced linux)
* Contribute documentation as needed (see examples above)

### Schedule

Packaging is rebuilt and released regularly (currently several times a week
because we are testing and finalizing 12.1), time dependent. I am in
communication with the Dash Core Team, but not a member of that team.

I hope to eventually fold the packaging into to Fedora's more formal release
engineering infrastructure and have Dash Core become automagically available to,
at least, all Fedora users. Eventually, the goal would be to integrate fully
into the Dash Core Team development as well and release engineering process,
though likely with my continued participation.

##### Milestones

What is left undone is packaging and automating some of items beyond core, in
particular and in the shorter term, building and packaging Sentinel. Also,
perhaps, adding in items like Dashman and other community delivered tools. A
whole suite of tooling.

Timeline and goals:

* Dash Core testnet: all builds within one week of availability.
* Dash Core mainnet: all builds within several days of availability.
* Underlying OS updates: Test and release all packaged offerings in conjunction with operating system updates. Fedora, for example, issues a new release every six months.
* Streamlining and re-org of current repositories: End of year, 2016
* Sentinel: Q1 2017
* Electrum: Unscoped at this point.
* Released to Fedora official repositories: Q1 2017 -- dependent on Fedora administrative acceptance

I have pored 8 months into what has been delivered already, and the project is
ongoing and indefinite. There is no "end date" to this effort, of course.

### Budget

What is being asked is a modest offset. A small patronage, if you will.

I use a personal linux machine (and virtualization), and several VPS instances
for development, packaging, and testing. These have their cost, but it is not
extreme. If accepted into the Fedora build system, some build costs will be
abstracted, and I will be able to leverage a larger talent pool of packaging
experts and automated professional testing. Additionally, that will expand the
supportable architectures for Dash Core (I only test 64 Intel), but that is a
less critical side benefit. Local personal testing will continue though.

**Most of my cost is time. Sometimes, a lot of time.**

***What are my costs for these "release engineering" efforts?***
* Hard costs:
  - Personal developer laptop
  - ~3 VPS instances for testing
* Time: 10+ hours a week

***For now, I am really just asking for a very modest cost offset for my
time<br />So I propose...***

#### Terms

> ***Three month honorarium/patronage...***
> * **99 DASH total**
>  * **33 DASH per month**
>  * **3 months**

> After 3 months, we will examine at how things are going and I will likely
request to renew with a similar proposal.

### Closing

Dash Core and its corresponding suite of tooling needs to be properly supported
on the Red Hat family of linux distributions. The software needs to be
professional built, tested,  packaged, improved and maintained over time. I am
providing some of that now and want to continue doing that well into the future.
The goodwill of the community is compensation enough, but if you can find it in
you to assist throught he budgeting process, it would be most welcome. Thank
you!
