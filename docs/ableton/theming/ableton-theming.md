# Ableton Theming

Custom themes for Ableton Live

## Installation

### Default Locations

Place the `.ask` file in the following location (or similar for the desired version of Ableton), then restart Ableton Live.

#### Windows

win: `C:\ProgramData\Ableton\Live 11 Suite\Resources\Themes`
mac: `/Applications/Ableton Live 11 Suite.app/Contents/App-Resources/Themes`

Some people install Ableton (or the beta) to a diff location, such as a local user folder by putting it in `/Users/<username>/Applications/Ableton Live <ver> Beta.app`, so make note of the desired path.

## Themes

### Light Themes

#### 1. Hello - Mid Light

A sensible theme that focuses on quality-of-life adjustments.

##### Grid, arrangement, and selection color changes

![ableton-highlighting](https://user-images.githubusercontent.com/2431707/142790979-7d547d91-90c4-4e62-9d43-c83fcd2ea07a.gif)

> Selection highlight is now not 100% opaque, allowing you to see sections and clips highlighted

##### Session view highlighting

![ableton-session](https://user-images.githubusercontent.com/2431707/142791347-14589b6d-8ac5-45d4-a3d9-5dc8f0850996.gif)

##### Clip envelope automation

![ableton-automation](https://user-images.githubusercontent.com/2431707/142790887-a061a9e6-e836-42af-8a72-e3a8e824365f.gif)

> Clip envelope automation now matches the track automation color scheme

### Dark Themes

```
TODO
```

## Theme Upgrade Guide

1. Make sure your theme is [compatible with the new version of Live by checking if it relies on any removed variables](./xml-attributes-changelog.md#steps-to-generate-diff).
2. Remove any attributes that are not used in the latest version.
3. Add new stylings to taste by adding the new tags to the theme.

You can check the added/removed variables here: [xml-attributes-changelog.md](./xml-attributes-changelog.md).
