# objective-c-playground [![Build status](https://travis-ci.org/twolfson/objective-c-playground.svg?branch=master)](https://travis-ci.org/twolfson/objective-c-playground)

Playground environment for learning Objective C and iOS

We've been using the following guides:

- [Start Developing iOS Apps Today by Apple (Objective-C version)](https://github.com/mrshyi/RoadMapiOS/blob/d78ec91c80903991c70124d37db54adf42a0c0c9/RoadMapiOS.pdf)

## Getting Started
To get this repo running locally, perform the following:

```bash
# Clone this repo
git clone git@github.com:twolfson/objective-c-playground.git
cd objective-c-playground

# Install our dependencies
# Nothing here yet...

# Open our project in Xcode
open objective-c-playground.xcodeproj

# Press the "Play" button
```

Upon pressing the "Play" button, there should be no compilation errors and the application will launch in a simulator

## Documentation
### Initial setup
We took the following steps to set up this repo:

- Create initial files (e.g. README, license)
- Create app via "Create new Xcode project" prompt in Xcode
    - Product Name: objective-c-playground
    - Team: None
    - Organization Name: Todd Wolfson
    - Organization Identifier: com.twolfson
    - Bundle Identifier (generated): com.twolfson.objective-c-playground
    - Language: Objective-C
    - [ ] Use Core Data
    - [x] Include Unit Tests
    - [x] Include UI Tests
    - Saved to this folder

## Questions/Answers
These are questions I've asked myself while learning

- Is there a slick way to bump versions via a script?
- What do tests look like?
- What does CI look like? What environments support it (e.g. TravisCI, CircleCI)
- What does package management look like? I think there's CocoaPods but can we verify that's the canonical tool?
    - Also, relevant from `.gitignore` template -- https://guides.cocoapods.org/using/using-cocoapods.html#should-i-check-the-pods-directory-into-source-control
- Explore Carthage, fastlane, and code injection mentioned in https://github.com/github/gitignore/blob/fad779220742a6d54ccfc0c1a0e5b3d820253de6/Objective-C.gitignore#L39-L63
- Are there tools like LiveReload to see changes immediately in-app?
    - Maybe something like a build server like Rails' `spring` or JS' `watchify` to reduce file system hits and general load times?
- How do we disable autoclosing strings/brackets/etc in Xcode?
- **We should visit the Shortcut Foo page for Xcode...**
- Can we add multi-cursor support like Sublime Text to Xcode?
    - Looks possible via some voodoo - <https://stackoverflow.com/a/34468037>
- What's the "Server & Bots" tab in Preferences for?
- Explore using SVGs as icons

## Tips and Tricks
- Browse "Preferences -> Key Bindings" to find slick shortcuts like:
    - Command+option+o - equivalent of Sublime Text's jump file
    - Command+r - Run
    - Command+t - Test
    - Ctrl+command+r - Run without building
    - Command+. - Stop
    - Shift+command+0 - Developer Documentation
- Here are my Xcode customization preferences: https://gist.github.com/twolfson/b7f73324219788ad4bb0d9cbccc6b7e6
- https://cocoacasts.com/seven-xcode-tricks-every-developer-should-know/

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style.

_(Testing coming soon)_

## Donating
Support this project and [others by twolfson][twolfson-projects] via [donations][twolfson-support-me].

<http://twolfson.com/support-me>

[twolfson-projects]: http://twolfson.com/projects
[twolfson-support-me]: http://twolfson.com/support-me

## Unlicense
As of Nov 16 2017, Todd Wolfson has released this repository and its contents to the public domain.

It has been released under the [UNLICENSE][].

[UNLICENSE]: UNLICENSE
