---
layout: releasenotes
title: SPICE 6 Release Notes
---

# SPICE 6 Release Notes

## 6.1001 (2020-07-24)
* **Note About System Requirements:** SPICE 6.1 now requires Mac OS version *10.13 or above* (6.0 required 10.9 or above) due to Apple's code signing and distribution requirements.
* **Note About Code Signing:** This bug-fix and maintenance update is provided by Gatera, LLC and is now code-signed with Apple by that name. If you receive a warning that the application's signing authority has changed, this is normal and valid. If you are uncertain, please make sure you've downloaded SPICE from its official site: https://niaid.github.io/spice/
* **Note About Updates:** This update removes automatic updating as SPICE is currently in "maintenance mode". All bug fix updates from this point forward (including this version) will only be announced here and will require you to download the application from the SPICE website in order to update.
* Fixed import bug that inappropriately claimed there were column naming errors in some files with specific characteristics.
* Fixed import bug that incorrectly treated some missing values as zero.
* Fixed bug when renaming a query, which required the query to be deselected and reselected to show the new name.
* Fixed bug that caused figures in the currently-selected figure to display incorrect values when the document is first opened, requiring a Cmd-R refresh to correct.
* The import process now automatically tries to parse matrix-formatted .spd for files with extensions other than .spd if tab- or comma-separated value parsing both fail.

## 6.0045 (2019-09-24)
* Fixed bug that prevented renaming a canvas.
* Removed all user statistics reporting.
* Updated support request behavior.

## 6.0044 (2019-07-22)

* Fixed bug that prevented empty canvas from rendering properly after adding initial figure reference.

## 6.0043 (2019-07-15)

* Color pickers now use the standard color panel due to issues with forcing it into a popover.
* Fixed help link in main menu.

## 6.0042 (2019-07-12)

* Registration is no longer required.
* Terms of use (attribution and EULA) updates.

## 6.0041 (2019-06-24)

* **Note to Pestle Users:** This update removes the "Download Pestle" links since Pestle version 2.0 is now available and is included with the main SPICE downloadable on the SPICE website ( [https://niaid.github.io/spice](https://niaid.github.io/spice) ). Because Pestle and SPICE are both standalone applications with their own auto-updating capabilities, *you will need to download the full distribution package to get the new version of Pestle*. That is, *this automatic update will not include Pestle 2.0*.

## 6.0040 (2019-04-11)

* Fixed a bug that prevented editing query groups with no figures. This also resolved related "hanging update" problems that could cause query updates to take longer than necessary or hang indefinitely until another query group or its figure was selected. This has the added benefit of saving time editing an empty query group and letting it update while adding figures (which will then use the available query results to run associated tests and plot).

## 6.0039 (2019-01-14)

* Fixed bug that could cause SPICE to crash when adding/running a pie permutation test with a high number of any combination of measurements, groups, overlays, and categories.
* Improved SPICE's behavior when running on Mojave under Dark Mode (this fix forces light/Aqua appearance).

## 6.0038 (2018-09-19)

* Added Big Obvious Help Button in toolbar.

## 6.0037 (2018-09-18)

* Fixed an import bug that could cause incorrect data and crashing errors to occur if imported data contains more than one measurement for the same category.

**Note:** *Documents created by importing tabular data into SPICE 6 should be recreated if they contain duplicate measurements as this will cause subtle errors at best and crashes at worst.*

## 6.0036 (2018-04-13)

* Fixed a drawing bug that caused pie charts - whose angles should add up to 360 degrees - to contain "bonus degrees".
* Fixed a permissions issue that could stall the auto-update mechanism at the "installing" stage for some users. **Note:** *If you are experiencing this issue, you will need to download and install manually the latest version from [https://niaid.github.io/spice](https://niaid.github.io/spice).*

## 6.0035 (2018-02-02)

* Fixes a bug that could cause SPICE to crash under certain circumstances when clicking a color swatch in the color scheme control.

## 6.0034 (2018-02-02)

This minor update addresses two issues:

* Fixes bug preventing opening of more than one document.
* Fixes multiple console log messages regarding iCloud Documents entitlements and related security.

## 6.0033 (2018-01-31)

**Public Release.** This is the final 6.0 public release version.