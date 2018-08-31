# TestFairy.Deploy.Android

Use it to upload your APK to TestFairy

Can be run directly with the [bitrise CLI](https://github.com/bitrise-io/bitrise),
just `git clone` this repository, `cd` into it's folder in your Terminal/Command Line
and call `bitrise run test`.

*Check the `bitrise.yml` file for required inputs which have to be
added to your `.bitrise.secrets.yml` file!*

## Trigger a new release

- __merge every code changes__ to the `master` branch
- __push the new version tag__ to the `master` branch