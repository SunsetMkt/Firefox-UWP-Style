# Firefox UWP Style

A theme that follows UWP styling.

## Install

Select the appropriate file:

- [Firefox Nightly](https://github.com/Guerra24/Firefox-UWP-Style/archive/refs/heads/nightly.zip)
- [Firefox 133-134](https://github.com/Guerra24/Firefox-UWP-Style/archive/refs/heads/firefox-133.zip)
- [Firefox 128-132](https://github.com/Guerra24/Firefox-UWP-Style/archive/refs/heads/firefox-128.zip)
- [Firefox 120-127](https://github.com/Guerra24/Firefox-UWP-Style/archive/refs/heads/firefox-120.zip)

Copy the content inside the folder where userChrome.css file is located into your *chrome* folder.

Toggle `toolkit.legacyUserProfileCustomizations.stylesheets` pref in `about:config` and restart Firefox.


## Styles

### MDL2

The original 2015 UWP design. Follows MDL2 styling with the accent color and gray-on-black or gray-on-white elements.

Enabled by default.

### Sun Valley

The 2021 Fluent Design refresh. Features heavy use of rounded corners and smoother colors.

Create boolean `uwp.sun-valley` pref to enable.

Create boolean `uwp.sun-valley.font` pref to enable Segoe UI Variable.

Create boolean `uwp.sun-valley.round-tabs` pref to enable rounded tabs.

Create boolean `uwp.sun-valley.colored-tabs` pref to enable colored tabs. It uses the container color or the accent color in default tabs. Only works with rounded tabs since the default ones have the tab line.

## Customize

Toggle `layout.css.backdrop-filter.enabled` pref to enable *acrylic blur* in some menus.

Toggle `widget.non-native-theme.use-theme-accent` pref to enable accent color in all *about:\** pages.

### Mica

**Only supported on Firefox 133 and newer**

Requires [MicaForEveryone](https://github.com/MicaForEveryone/MicaForEveryone) and only works with *Sun Valley* style

In MicaForEveryone create a process rule and select `firefox` then set the backdrop type to your preferred one.

Create boolean `uwp.sun-valley.mica` pref to enable.

Toggle `browser.tabs.allow_transparent_browser` pref to enable transparency support in all pages.

### Custom CSS

If you want to change any rules use `customChrome.css` and `customContent.css`.

All the theme vars `--uwp-*` can be overridden, Firefox vars too but only if they are not set using `!important`.

### Accent Color

If you want to override the accent color create two new prefs, both string type set to RGB Hex values.

`ui.accentcolor`=`#FF00FF` Accent color

`ui.accentcolortext`=`#FFFFFF` Text color when the background is the accent color.

## Screenshots (Sun Valley)

![01](https://s3.guerra24.net/projects/firefox-uwp/screenshots/01.png)
![02](https://s3.guerra24.net/projects/firefox-uwp/screenshots/02.png)
![04](https://s3.guerra24.net/projects/firefox-uwp/screenshots/03.png)
![05](https://s3.guerra24.net/projects/firefox-uwp/screenshots/04.png)
![05](https://s3.guerra24.net/projects/firefox-uwp/screenshots/05.png)
![06](https://s3.guerra24.net/projects/firefox-uwp/screenshots/06.png)
<!---
![07](https://s3.guerra24.net/projects/firefox-uwp/screenshots/07.png)
![08](https://s3.guerra24.net/projects/firefox-uwp/screenshots/08.png)
-->
![09](https://s3.guerra24.net/projects/firefox-uwp/screenshots/09.png)
