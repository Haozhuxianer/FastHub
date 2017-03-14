[![Build Status](https://travis-ci.org/k0shk0sh/FastHub.svg?branch=master)](https://travis-ci.org/k0shk0sh/FastHub)
[![codecov](https://codecov.io/gh/k0shk0sh/FastHub/branch/master/graph/badge.svg)](https://codecov.io/gh/k0shk0sh/FastHub)

![Logo](/.github/assets/feature_graphic.png?raw=true "Logo")

# FastHub  

Yet another **open-source** GitHub client app but unlike any other app, FastHub was built from scratch.
 
 
## Download
 
 **FastHub** can be downloaded on [Google Play](https://play.google.com/store/apps/details?id=com.fastaccess.github):
 
 <a href="https://play.google.com/store/apps/details?id=com.fastaccess.github">
     <img alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" height="80px"/>
 </a>
 
_(To download the app from here, please look at the [latest release](https://github.com/k0shk0sh/FastHub/releases/latest).)_
 
# Features

- **App**
  - Offline-mode
  - Markdown and code highlighting support
  - Notifications overview and "Mark all as read"
- **Repositories**
  - Search Repos
  - Browse and search Repos
  - See your public, private and forked Repos
  - Filter Branches and Commits
  - Watch, star and fork Repos
  - Download releases and files
- **Issues and Pull Requests**
  - Search Issues/PRs
  - Open/close Issues/PRs
  - Comment on Issues/PRs
  - Manage Issue/PR comments
  - Edit Issues/PRs
  - Lock/unlock conversation in Issues/PRs
  - Assign people and add Labels and Milestones to Issues/PRs
  - Manage Milestones
- **Commits and Gists**
  - Search Code/Gists
  - View Gists and their files
  - Comment on Commits/Gists
  - Manage Commit/Gist comments
  - Create/Delete Gists
- **Users**
  - Follow/unfollow users
  - Search Users, Repos, Issues,Pull Requests and Code
- _**Much more...**_
  - _FastHub is actively developed. More features will come!_

> **FastHub** contain Ads, which are disabled by default. You could enable them if you'd like to support the development.

# Specs / Open-source libraries:

- Minimum **SDK 21**, _but AppCompat is used all the way ;-)_
- **MVP**-architecture: [**ThirtyInch**](https://github.com/grandcentrix/ThirtyInch) is used to simplify maintaining and adding features.
- **Lambda** expressions because _you know why :-)_
- [**RxJava**](https://github.com/ReactiveX/RxJava) & [**RxAndroid**](https://github.com/ReactiveX/RxAndroid) for Retrofit & background threads
- [**Retrofit**](https://github.com/square/retrofit) for constructing the REST API
- [**SqliteMagic**](https://github.com/SiimKinks/sqlitemagic) for offline-mode
- [**Stream API**](https://github.com/aNNiMON/Lightweight-Stream-API) for dealing with `ArrayLists`
- **JobScheduler** using Firebase JobDispatcher for notifications service.
- [**ButterKnife**](https://github.com/JakeWharton/butterknife) for view binding
- [**Icepick**](https://github.com/frankiesardo/icepick) for saving instance states
- [**Lombok**](https://projectlombok.github.io) for getters and setters
- [**Material-BottomNavigation**](https://github.com/sephiroth74/Material-BottomNavigation) for `Fragment` navigation
- [**Android-Universal-Image-Loader**](https://github.com/nostra13/Android-Universal-Image-Loader) for loading images
- [**MarkDown**](https://github.com/zzhoujay/Markdown) for _Markdown_ editor highlighting
- [**Toasty**](https://github.com/GrenderG/Toasty) for displaying error/success messages
- [**ShapedImageView**](https://github.com/gavinliu/ShapedImageView) for round avatars
- [**MatrialTapTargetPrompt**](https://github.com/sjwall/MaterialTapTargetPrompt) for displaying tips throughout the app
- **Firebase** analytics, crash reporting, ads
- **Android Support Libraries**, the almighty ;-)

# Contribution

You love FastHub? You want new features or bug fixes?  
Please **contribute** to the  project either by [_creating a PR_](https://github.com/k0shk0sh/FastHub/compare) or [_submitting an issue_](https://github.com/k0shk0sh/FastHub/issues/new) on GitHub.  
Read the [**contribution guide**](CONTRIBUTE.md) for more detailed information.

# License

> Copyright (C) 2017 Kosh. 
> Licensed under the [GPL-3.0](https://www.gnu.org/licenses/gpl.html) license.
> (See the [LICENSE](https://github.com/k0shk0sh/FastHub/blob/master/LICENSE) file for the whole license text.)

# Screenshots _(old ones, they will be updated soon)_

| Mobile Portrait | Mobile Landscape |
|:-:|:-:|
| ![Main Screen](/.github/assets/mobile_main.png?raw=true) | ![Main Screen Landscape](/.github/assets/mobile_main_landscape.png?raw=true) |

| Repo (Tablet) | Commit (Tablet) |
|:-:|:-:|
| ![Main Screen Repo](/.github/assets/tablet_repo.png?raw=true) | ![Main Screen Commit](/.github/assets/tablet_commits.png?raw=true) |
