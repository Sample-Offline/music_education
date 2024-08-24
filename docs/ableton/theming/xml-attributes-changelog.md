# XML Attributes Changelog

Document Version: `1.0`
Latest version of live diff'd: `12.0b9`

## Live 12.0b9

### Added

These are **_new_** attributes available since Live 12.

#### List

```xml
<BrowserTagBackground />
<DeactivatedClipHeader />
<DeactivatedClipHeaderForeground />
<MainViewFocusIndicator />
<MidiEditorBackgroundWhiteKeySeparator />
<MidiEditorBlackKeyBackground />
<PianoBlackKey />
<PianoKeySeparator />
<PianoWhiteKey />
<RangeEditField3 />
<RetroDisplayTitle />
<ScaleAwareness />
<ScrollbarInnerHandleHover />
<ScrollbarInnerTrackHover />
<ScrollbarLCDHandleHover />
<ScrollbarLCDTrackHover />
<ScrollbarMixerShowOnScrollHandle />
<ScrollbarMixerShowOnScrollHandleHover />
<SessionSlotOklabLCompensationFactor />
<TransportOffForeground />
<ViewControlOff />
<ViewControlOn />
<BelowZeroDecibel1 />
<BelowZeroDecibel2 />
```

#### Types

|Attribute|Type/Description|
|---|---|
|`<BrowserTagBackground />`|`hex`<br>Example: `#ffffff`|
|`<DeactivatedClipHeader />`|`hex`<br>Example: `#ffffff`|
|`<DeactivatedClipHeaderForeground />`|`hex`<br>Example: `#ffffff`|
|`<MainViewFocusIndicator />`|`hex`<br>Example: `#ffffff`|
|`<MidiEditorBackgroundWhiteKeySeparator />`|`hex` with alpha value<br>Example: `#29292919`|
|`<MidiEditorBlackKeyBackground />`|`hex` with alpha value<br>Example: `#1f1f1f19`|
|`<PianoBlackKey />`|`hex`<br>Example: `#ffffff`|
|`<PianoKeySeparator />`|`hex`<br>Example: `#ffffff`|
|`<PianoWhiteKey />`|`hex`<br>Example: `#ffffff`|
|`<RangeEditField3 />`|`hex`<br>Example: `#ffffff`|
|`<RetroDisplayTitle />`|`hex`<br>Example: `#ffffff`|
|`<ScaleAwareness />`|`hex`<br>Example: `#ffffff`|
|`<ScrollbarInnerHandleHover />`|`hex`<br>Example: `#ffffff`|
|`<ScrollbarInnerTrackHover />`|`hex`<br>Example: `#ffffff`|
|`<ScrollbarLCDHandleHover />`|`hex`<br>Example: `#ffffff`|
|`<ScrollbarLCDTrackHover />`|`hex`<br>Example: `#ffffff`|
|`<ScrollbarMixerShowOnScrollHandle />`|`hex` with alpha value<br>Example: `#00000066`|
|`<ScrollbarMixerShowOnScrollHandleHover />`|`hex` with alpha value<br>Example: `#0000004c`|
|`SessionSlotOklabLCompensationFactor`|`int`<br>Example: `58`|
|`<TransportOffForeground />`|`hex`<br>Example: `#ffffff`|
|`<ViewControlOff />`|`hex`<br>Example: `#ffffff`|
|`<ViewControlOn />`|`hex`<br>Example: `#ffffff`|
|`<BelowZeroDecibel1 />`|`hex`<br>Example: `#ffffff`|
|`<BelowZeroDecibel2 />`|`hex`<br>Example: `#ffffff`|

### Removed

These are attributes available in Live 11, but **_removed_** from Live 12.

#### List

```xml
<ScrollbarOuterHandle />
<ScrollbarOuterTrack />
<SearchIndicationStandby />
<SurfaceAreaForeground />
<ZoomPanHandle />
```

## Steps to Generate diff

1. Sort attr under `<Theme>` by name asc or whatever
2. `diff file1-live11theme.ask file2-live12theme.ask`
3. Make note of any attr added or removed
