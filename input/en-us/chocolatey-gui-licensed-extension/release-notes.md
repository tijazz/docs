---
Order: 10
xref: chocolatey-gui-licensed-extension-release-notes
Title: Release Notes
Description: Release Notes for Chocolatey GUI Extension
---

# Chocolatey Release Notes - Chocolatey GUI Licensed Extension
## Summary
This covers the release notes for the Chocolatey GUI Licensed Extension (`chocolateygui.extension`) package, where the commercial editions of Chocolatey GUI get their enhanced functionality.
Please see [Install the Licensed Edition](xref:setup-chocolatey-gui-licensed) for information on how to get and install the package.

> :memo: **NOTE** This package is available to Chocolatey for Business customers only.

## Other Release Notes
* Refer to [Open Source Release Notes](xref:floss-release-notes) as commercial editions build on top of open source.
* Chocolatey for Business (C4B) customers - also refer to [Chocolatey Agent Release Notes](xref:agent-release-notes) and [Chocolatey Central Management Release Notes](xref:ccm-release-notes).

## 0.3.0 (September 6, 2021)

> :warning: **WARNING**
>
> The dependencies of the chocolateygui.extension package have changed in this release, and it now requires Chocolatey CLI v0.11.1 and Chocolatey GUI v0.19.0.

### FEATURES
* Add feature to allow disabling of the This PC source - see [licensed #228](https://github.com/chocolatey/chocolatey-licensed-issues/issues/228)
* Add feature to allow disabling of "Update All" button -see [licensed #240](https://github.com/chocolatey/chocolatey-licensed-issues/issues/240)

### IMPROVEMENTS
* [Security] XML External Entity attack in log4net (CVE-2018-1285) see [licensed #254](https://github.com/chocolatey/chocolatey-licensed-issues/issues/254)

### Release Video

A short video explaining what is included in this release can be found here:

<p>
<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/O0fyUHe2pb8?list=PL84yg23i9GBjSzAEmtCqSLf2us_LLIDwZ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>
<br>
</p>

## 0.2.1 (March 29, 2021)

### BUGS
* Fix - Incorrect configuration database being used by Chocolatey GUI Licensed Extension when running as non-administrator user - see [licensed #209](https://github.com/chocolatey/chocolatey-licensed-issues/issues/209)

### Release Video

A short video explaining what is included in this release can be found here:

<p>
<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/t4h3Y9GMIrc?list=PL84yg23i9GBjSzAEmtCqSLf2us_LLIDwZ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>
<br>
</p>

## 0.2.0 (March 9, 2021)

### BREAKING CHANGES
* Update the default value for "NonAdmin Access to Settings" feature to be false - see [#601](https://github.com/chocolatey/ChocolateyGUI/issues/601)

### FEATURES
* Provide ability for Chocolatey GUI to respect the background service allowed commands configuration option
* Add a feature to toggle on/off a read only view for installed packages - see [licensed #201](https://github.com/chocolatey/chocolatey-licensed-issues/issues/201)
* Add a feature to toggle on/off the option to not attempt to download icons for packages - see [licensed #199](https://github.com/chocolatey/chocolatey-licensed-issues/issues/199)
* Add a configuration option to specify a default for a particular source when application loads - see [licensed #198](https://github.com/chocolatey/chocolatey-licensed-issues/issues/198)

### Release Video

A short video explaining what is included in this release can be found here:

<p>
<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/tug8P1wxXmY?list=PL84yg23i9GBjSzAEmtCqSLf2us_LLIDwZ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>
<br>
</p>

## 0.1.0 (January 22, 2021)

Initial preview release

### FEATURES
* Branding - Support for branding portions of the Chocolatey GUI assets from provided assets
* Provide ability to restrict access to Chocolatey GUI settings to only machine administrators
* Packaging - Extension is deployable in the same way as the Chocolatey Licensed Extension
* Provide visual indication in Chocolatey GUI when the Chocolatey GUI Licensed Extension is being used

### Release Video

A short video explaining what is included in this release can be found here:

<p>
<div class="ratio ratio-16x9">
    <iframe src="https://www.youtube.com/embed/kypWt1UyVwg?list=PL84yg23i9GBjSzAEmtCqSLf2us_LLIDwZ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>
</div>
<br>
</p>
