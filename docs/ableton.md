# Ableton Cheatsheet

## Clip automation

Automation envelopes in the **Clip View** are dependent on the warping algo used (Beats, tones, texture, etc.)

## Grouping

Grouped tracks use a single CPU thread. Ungrouped tracks use a thread-per-track.

## Unpack `.als` files to `.xml`

Haven't found an easy way to convert back and have it still be usable, but you can `git commit` the `.xml` file and diff the changes, if need be for whatever reason using the following:

```sh
gzip -cd MySong.als > MySong.xml
```
