## airG
airG is a pioneer in the mobile software industry having released its first mobile application in 2000. Since then the company's products and services have been used by over 100 million consumers globally, generating more than $1 billion in revenues. Our products inform, entertain and connect.

## airG Open Source
airG Open Source is a collection of open source libraries, published under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

### [Android Async](https://airg.github.io/android-async)
The airG android async library is a group of utilities for easier management of asynchronous tasks. The main components of this library are:

* __ThreadPool__ allows you to easily run tasks on a background or the main (UI) thread from anywhere.
* __AsyncHelper__ helps you determine (and assert) whether a specific piece of code runs on the UI or background thread.
* __Promises__ allow you to run tasks asynchronously and be informed when each task is completed, cancelled, or failed.

### [Android Device](https://airg.github.io/android-device)
The airG android device library provides a collection of utility methods for getting runtime information about the device such as API Level, Camera availability, Connectivity, Soft Keyboard utilities, and generic hardware information

### [Android Logging](https://airg.github.io/android-logging)
The airG android logging library provides formatted and tagged logging for Android so that you can

 * Tag once and log often
 * Use `String.format` style formatting for log messages.

### [Android Miscellaneous Library](https://airg.github.io/android-misc)
The airG Miscellaneous library gives you useful bits of functionality that are too small to be their own library, but useful enough to be needed in more than one place.

### [Android Runtime Permissions](https://airg.github.io/android-rtpermissions)
The airG Runtime Permissions library provides an easy way to handle handle Marshmallow's runtime permissions from any Fragments or activity, paving our way to everlasting Android fame.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">To make a name for yourself in the open source community, start by creating an image loading library or permissions helper. <a href="https://twitter.com/hashtag/androidBadvice?src=hash">#androidBadvice</a></p>&mdash; Bad Android Advice (@anddev_badvice) <a href="https://twitter.com/anddev_badvice/status/821743607917015041">January 18, 2017</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## Contributing
Contributions are appreciated and welcome. In order to contribute to any of the above libraries, follow these easy steps:

 1. Write a clear and concise description of your change refer to issue tracker ids where available (ideally, you'd file an issue with this information).
 1. Fork the repo
 1. Make your changes (besure to format your code according to the included codestyle settings)
 1. Add tests or usage examples where applicable (i.e. update the tests and samples) and make sure they pass.
 1. Add the original repo as your `upstream` repo (`git remote add upstream <repo-url>`)
 1. Rebase (skipping this step is an easy way to disqualify your commit).
 1. Submit a pull request and reference the issue id as well as the paragraph in #1 above.
