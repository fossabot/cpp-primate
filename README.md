# {Name}

Build Status
The current development branch is master. It builds for .NET Core and the full desktop .NET framework. Changes in master will go into the next "major" update of MSBuild.

Runtime\OS	Windows	Ubuntu 14.04	Ubuntu 16.04	Mac OS X
Full Framework	Build Status	N/A	N/A	N/A
.NET Core	Build Status	Build Status	Build Status	Build Status
Mono



### Build Status

The current development branch is `master`. It builds for .NET Core and the full desktop .NET framework. Changes in `master` will go into the next "major" update of MSBuild.

| Runtime\OS | Windows | Ubuntu 14.04 | Ubuntu 16.04 |Mac OS X|
|:------|:------:|:------:|:------:|:------:|
| **Full Framework** |[![Build Status](https://ci2.dot.net/buildStatus/icon?job=Microsoft_msbuild/master/innerloop_Windows_NT_Full)](https://ci2.dot.net/job/Microsoft_msbuild/job/master/job/innerloop_Windows_NT_Full)| N/A | N/A | N/A |
|**.NET Core**|[![Build Status](https://ci2.dot.net/buildStatus/icon?job=Microsoft_msbuild/master/innerloop_Windows_NT_CoreCLR)](https://ci2.dot.net/job/Microsoft_msbuild/job/master/job/innerloop_Windows_NT_CoreCLR)|[![Build Status](https://ci2.dot.net/buildStatus/icon?job=Microsoft_msbuild/master/innerloop_Ubuntu14.04_CoreCLR)](https://ci2.dot.net/job/Microsoft_msbuild/job/master/job/innerloop_Ubuntu14.04_CoreCLR)|[![Build Status](https://ci2.dot.net/buildStatus/icon?job=Microsoft_msbuild/master/innerloop_Ubuntu16.04_CoreCLR)](https://ci2.dot.net/job/Microsoft_msbuild/job/master/job/innerloop_Ubuntu16.04_CoreCLR)|[![Build Status](https://ci2.dot.net/buildStatus/icon?job=Microsoft_msbuild/master/innerloop_OSX_CoreCLR)](https://ci2.dot.net/job/Microsoft_msbuild/job/master/job/innerloop_OSX_CoreCLR)|
|**Mono**|returning soon|

We have entered stabilization for the 15.3 release (corresponding to Visual Studio 15.3) in the [`vs15.3`](https://github.com/Microsoft/msbuild/tree/vs15.3) branch.

| Runtime\OS | Windows | Ubuntu 14.04 | Ubuntu 16.04 |Mac OS X|
|:------|:------:|:------:|:------:|:------:|
| **Full Framework** |[![Build Status](https://ci2.dot.net/buildStatus/icon?job=Microsoft_msbuild/vs15.3/innerloop_Windows_NT_Full)](https://ci2.dot.net/job/Microsoft_msbuild/job/vs15.3/job/innerloop_Windows_NT_Full)| N/A | N/A | N/A |
|**.NET Core**|[![Build Status](https://ci2.dot.net/buildStatus/icon?job=Microsoft_msbuild/vs15.3/innerloop_Windows_NT_CoreCLR)](https://ci2.dot.net/job/Microsoft_msbuild/job/vs15.3/job/innerloop_Windows_NT_CoreCLR)|[![Build Status](https://ci2.dot.net/buildStatus/icon?job=Microsoft_msbuild/vs15.3/innerloop_Ubuntu14.04_CoreCLR)](https://ci2.dot.net/job/Microsoft_msbuild/job/vs15.3/job/innerloop_Ubuntu14.04_CoreCLR)|[![Build Status](https://ci2.dot.net/buildStatus/icon?job=Microsoft_msbuild/vs15.3/innerloop_Ubuntu16.04_CoreCLR)](https://ci2.dot.net/job/Microsoft_msbuild/job/vs15.3/job/innerloop_Ubuntu16.04_CoreCLR)|[![Build Status](https://ci2.dot.net/buildStatus/icon?job=Microsoft_msbuild/vs15.3/innerloop_OSX_CoreCLR)](https://ci2.dot.net/job/Microsoft_msbuild/job/vs15.3/job/innerloop_OSX_CoreCLR)|

[![Join the chat at https://gitter.im/Microsoft/msbuild](https://badges.gitter.im/Microsoft/msbuild.svg)](https://gitter.im/Microsoft/msbuild?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
















<!-- Replace this badge with your own-->
[![Build status](https://ci.appveyor.com/api/projects/status/hv6uyc059rqbc6fj?svg=true)](https://ci.appveyor.com/project/madskristensen/extensibilitytools)

<!-- Update the VS Gallery link after you upload the VSIX-->
Download this extension from the [VS Gallery](https://visualstudiogallery.msdn.microsoft.com/[GuidFromGallery])
or get the [CI build](http://vsixgallery.com/extension/{ID}/).

---------------------------------------

{Description}

See the [change log](CHANGELOG.md) for changes and road map.

## Features

- Feature 1
- Feature 2
  - Sub feature

### Feature 1
Describe feature 1. Add screenshots/code samples etc.

### Feature 2
Describe feature 2. Add screenshots/code samples etc.

#### Sub feature
Describe sub feature. Add screenshots/code samples etc.

## Contribute
Check out the [contribution guidelines](CONTRIBUTING.md)
if you want to contribute to this project.

For cloning and building this project yourself, make sure
to install the
[Extensibility Tools 2015](https://visualstudiogallery.msdn.microsoft.com/ab39a092-1343-46e2-b0f1-6a3f91155aa6)
extension for Visual Studio which enables some features
used by this project.

## License
[Apache 2.0](LICENSE)




## Synopsis

At the top of the file there should be a short introduction and/ or overview that explains **what** the project is. This description should match descriptions added for package managers (Gemspec, package.json, etc.)

## Code Example

Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Motivation

A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Installation

Provide code examples and explanations of how to get the project.

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests

Describe and show how to run the tests with code examples.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)







# Project Title

One Paragraph of project description goes here

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc

