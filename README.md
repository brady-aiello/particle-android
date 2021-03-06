<p align="center">
<img src="particle-mark.png" alt="Particle" title="Particle">
</p>

# Particle Android libraries and apps

[Install the Tinker app on your Android device from the Google Play Store](https://play.google.com/store/apps/details?id=io.particle.android.app)


This repository is a convenient single location for all Android-related code released by Particle.  Currently, this includes:
- the Particle [Cloud SDK](https://github.com/particle-iot/particle-android/tree/master/cloudsdk)
- the Particle [Device Setup Library](https://github.com/particle-iot/particle-android/tree/master/devicesetup) (for Particle Gen 2 devices)
- the [Tinker app](https://github.com/particle-iot/particle-android/tree/master/app)


## Getting started with the libraries, getting help, and everything else

Full documentation, including a getting started guide, lots of API examples, support & feedback links, and more are all available from our documentation page: https://docs.particle.io/reference/android/


### Additional resources
* Read the getting started guide at https://particle.io/start
* Join the most active and helpful IoT community out there at https://community.particle.io
* Learn more about Particle syntax and hardware at https://docs.particle.io
* Start building your own code at https://particle.io/build
* Find answers to common questions at https://support.particle.io


### Requirements for building the Tinker app

1. Get [the latest stable version of Android Studio](https://d.android.com/studio/)
2. Once you have Android Studio installed, launch it, and from the "Welcome to Android Studio" screen, pick "Open an existing Android Studio project".  When it prompts you for the project location, point it at the top-level 'build.gradle' file in the repo.
3. Once AS has finished its initial cogitating on the project, hit the "play" button on the toolbar to build and run the app on a device.


## Release Cadence

As described at the top of the document, there are three distinct products produced by this repo.  Any time one of modules for these products changes on `master`, we will ship a release which includes that change within 90 days.

(Note: while it is our intent to release on this schedule, it is not meant as a guarantee. Circumstances may require us to expand the window between a change and when that change ships in a release.)


## Maintainers

- Jens Knutson [Github](https://github.com/jensck/) | [Twitter](https://twitter.com/jensknutson)

### Maintainer docs
[`RELEASING.md`](RELEASING.md)


## License

All code in this repository is available under the Apache License 2.0.  See the `LICENSE` file for the complete text of the license.
