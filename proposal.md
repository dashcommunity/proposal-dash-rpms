Dash Core software professionally packaged, tested, maintained, and delivered
for the Fedora, CentOS, and RHEL linux platforms.

### Overview

This is a request to fund the ongoing process of building, packaging, and
delivery of Dash Core code for the premier family of linux operating systems:
Red Hat -- Fedora, CentOS and RHEL. I have been building packages for this line
of operating systems for approximately 8 months now and will continue to do so,
proposal accepted or not. This is a plea to help fund my efforts as I improve
and expand the scope of what I am already doing.

*...more detail...*

A mature software application ideally needs mature packaging for the various
permutations of operating system platforms on which it runs. Examples: for
Ubuntu this means .deb (for apt-get automation), for MacOS this means .pkg, etc.
For the Red Hat linux family of operating systems -- Fedora, CentOS, RHEL --
this means RPM packages (.rpm).

The advantages are that you build these packages consistently and they allow
predictable and easy installation for users. They pull in the dependencies they
need without the user having to think about them, and the operating system can
track and manage updates cleanly and efficiently.

Today, I developed the packaging specs, build and digitally sign packages and
make them available. I have also written installation configuration instruction
tailered to these builds and these platforms. But there is a lot more to be done
to really professionalize the product for this family of operating systems.

**Who am I?** I am dAgrarian (forums), taw00 (github), t0dd and agrarian (other
places).

### Scope

I build and test on a number of local virtual and VPS instances for both stable
(currently 0.12.0.58) and testnet (0.12.1) Dash Core. This will continue
indefinitely and expand in scope.

##### Deliverables

* Source packages: https://github.com/taw00/dashcore-srpms
* Binary packages: https://drive.google.com/open?id=0B0BT-eTEFVLORG03ck1tem1idEE
* General usage instruction: https://drive.google.com/open?id=18qwFkDKfyZhvecuR5kxiIKmPsjPZjFhRY0EsfHYbD7I
* Tailored testnet masternode guidance: https://gist.github.com/taw00/e978f862ee1ad66722e16bcc8cf18ca5
* You can find many of my announcements in the Dash Forums such as [this one](https://www.dash.org/forum/threads/12-1-testnet-testing-phase-two-ignition.10818/page-8#post-108491), [this one](https://www.dash.org/forum/threads/testnet-masternode-guide-for-fedora-centos-rhel.11950/), and [this one](https://www.dash.org/forum/threads/12-1-testnet-testing-phase-two-ignition.10818/page-6#post-106852) (I don't announce every test build)

Aspirationally, I strive to...

* Drive Dash Core into Fedora's formal release process and official repositories
* Drive the build process into the Dash Core Team's formal release processes
* Expand the set of packages beyond core, for example, the Electrum wallet, Sentinel, etc.
* Make Dash Core SELinux-friendly
* Contribute documentation as needed

### Schedule

Testnet packaging is rebuilt and released regularly several times a week, time
dependent. Often daily. I am in communication with the Dash Core Team, but not a
member of that team.

I hope to eventually fold the packaging into to Fedora's more formal release
engineering infrastructure and have Dash Core become automagically available to,
at least, all Fedora users. Eventually, the goal would be to integrate fully
into the Dash Core Team development and release engineering process, though with
my continued participation.

##### Milestones

What is left undone is packaging and automating some of items beyond core, in
particular and in the shorter term, building and packaging Sentinel. Also,
perhaps, adding in items like Dashman and other community delivered tools.

Timeline and goals:

* Dash Core testnet: all builds within one week of availability.
* Dash Core stable: all builds within several days of availability.
* Streamlining and re-org of current repositories: end of year, 2016
* Sentinel: Q1 2017
* Electrum: unscoped at this point.
* Released to Fedora official repositories: Q1 2017 -- dependent on Fedora administrative acceptance

I have pored 8 months into what has been delivered already, and the project is
ongoing and indefinite. There is no "end date" to this effort, of course.

### Budget

I use a personal linux machine (and virtualization), and several VPS instances
for development, packaging, and testing. These have their cost, but it is not
extreme. If accepted into the Fedora build system, some build costs will be
abstracted, and I will be able to leverage a larger talent pool of packaging
experts and automated professional testing. Additionally, that will expand the
supportable architectures for Dash Core (I only test 64 Intel), but that is a
less critical side benefit. Local personal testing will continue though.

Most of my cost is time. Sometimes, *a lot* of time.

* Hard costs:
  - Personal developer laptop: $0 for now
  - VPS instances for testing: 3 x $5 per month
* Time: est. ave. 10 hours a week at $50 per hour, let's call it $2000 per month

##### Terms

Above we ballparked $2000 per month on the open market or 226 DASH / month (as
of this writing, $8.84/DASH). But, for now, I am really just asking for an
offsetting donation of DASH for my time. So I propose...

Terms:

* 1000 DASH total
 * 167 DASH per month
 * 6 months

After 6 months, we will examine at how things are going and likely renew with a similar proposal.

### Closing

The Red Hat family of linux distributions needs professional build, testing, and packaging. I am providing some of that now and want to continue doing that well into the future. The goodwill of the community is compensation enough, but if you can find it in you to help monetarily, it would be most welcome. Thank you!
