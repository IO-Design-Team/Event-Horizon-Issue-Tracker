---
name: Launchpad item preset request
about: Request a preset
title: "[PRESET] "
labels: ''
assignees: ''

---

**App name**
The name of the app you would like to have a preset

**App Store link**
A link to the app on the App Store

**Launch URL**
The URL Event Horizon will use to open the app

<details>

<summary>How to find launch URLs</summary>

1. Download an IPA of the app from [here](https://armconverter.com/decryptedappstore)
2. Extract the IPA using an app like [Keka](https://www.keka.io)
3. Right click the extracted IPA and click `Show Package Contents`
4. Open the `Info.plist` file and find the `CFBundleURLSchemes` section
5. Try the URLs in Event Horizon until you find one that launches the app without issues. Not all apps will support this. For example, if the URL scheme is `msteams` put `msteams://` into the `Launch URL` field in Event Horizon.
6. Paste the URL above

</details>

Failure to fill out all the above information
