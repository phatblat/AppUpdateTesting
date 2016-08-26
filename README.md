# AppUpdateTesting

Mock JSON for app update service

## Examples

- [supported.json](https://github.com/phatblat/AppUpdateTesting/blob/master/examples/supported.json) - No new version, you're on the latest
- [retired.json](https://github.com/phatblat/AppUpdateTesting/blob/master/examples/retired.json) - This app has been retired
- [mustupgrade.json](https://github.com/phatblat/AppUpdateTesting/blob/master/examples/mustupgrade.json) - Force upgrade to new version
- [notsupported.json](https://github.com/phatblat/AppUpdateTesting/blob/master/examples/notsupported.json) - Current OS is not supported by latest version


## Changing the App Update Behavior

It may help to open the [examples](https://github.com/phatblat/AppUpdateTesting/tree/master/examples) folder in another browser tab or window before changing the "current" file.

1. Edit the [current.json](https://github.com/phatblat/AppUpdateTesting/edit/master/current.json) file
1. Replace the contents of the file with the contents of an example you want to test with
1. Click the "Commit changes" button to save
1. You can review what is in [current.json](https://github.com/phatblat/AppUpdateTesting/blob/master/current.json) at any time
1. Set it back to [supported.json](https://github.com/phatblat/AppUpdateTesting/blob/master/examples/supported.json) when done testing
