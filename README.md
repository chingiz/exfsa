# Export From SketchApp and Arrange for Android Studio

This shell script is for arranging exported assets from sketchapp for Android Development.

## Install

The following installs the script making it system-available.

```
$ git clone git@github.com:Chingiz/exfsa.git
$ cd exfsa
$ sudo cp exfsa /usr/bin
```

## How to use

### Export asset from SketchApp

Export the assets from SketchApp with the appropriate suffixes. 
Make sure there are no whitespaces in the filenames.

Required suffixes:
- @1x
- @2x
- @3x
- @1.5x
- @4x

#### Exporting guide:

Select the element to export

![Selected Element](/screenshots/selection.png?raw=true  "Selected Element")

Make it exportable and fill the sizes and suffixes

![Exported Settings](/screenshots/settings.png?raw=true  "Exported Settings")

Export the assets to a folder. They will look like this:

![Exported Assets](/screenshots/assets.png?raw=true  "Exported Assets")

### Run the `exfsa` script

This will rename the assets with place them in the appropriate folders.

```
$ exfsa
```

### Final result

![Final Result](/screenshots/final.png?raw=true  "Final Result")

## License
MIT © Chingiz Huseynzade
