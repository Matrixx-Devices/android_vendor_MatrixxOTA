### Matrixx OTA repo
In order for a device to be officially supported by Matrixx, OTA information needs to be added.
Please refer to the following "Readme" to get started

### Introduction
In order for a device to be OTA compliant, there are a few things to know.

### JSON structure
```
{
  "response": [
    {
        "maintainer": "mukesh22584",
        "oem": "OnePlus",
        "device": "lemonadep",
        "filename": "Matrixx-v10.0-Official-lemonadep-Gapps-20231212.zip",
        "download": "https://sourceforge.net/projects/my-builds/files/Test/Matrixx-v10.0-Official-lemonadep-Gapps-20231212.zip/download",
        "timestamp": 1702364071,
        "md5": "0dc96940d550e2fd4387be4f8f309014",
        "size": 1877620187,
        "version": "v10.0"
    }
  ]
}
```
### Generate JSON
- JSON file wii be generated automatically into ```vendor/MatrixxOTA```
- Just add, commit and push

### Add changelog link
- Add your device changelog path in your device overlay:
```
overlay/packages/apps/Updater/app/src/main/res/values/config.xml
```
- Example: ```<string name="menu_changelog_url" translatable="false">https://matrixx-devices.github.io/mi/marble.html</string>```

### Guidelines
* Check if manufacturer is already existing
* Check if published link is official
* Check if JSON is intact with help of online validator tools like [https://jsonformatter.curiousconcept.com](https://jsonformatter.curiousconcept.com) or [https://jsonformatter.org](https://jsonformatter.org)
* Check if no extra / missing spaces
