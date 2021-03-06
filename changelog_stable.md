# YASAN Launcher Changelog

## 0.8.14

- Fix some icon loading issues.

## 0.8.13

- Fix AI related issues from the v0.8.10 update.

## 0.8.12

- Fix miscellaneous issues from the v0.8.10 update.

## 0.8.11

- Fix crashes on old installs.

## 0.8.10

- Major internal changes to optimize how apps & their icons are loaded.
- Fixed Home apps taking too long to load sometimes after the v0.8.8 update.
- Switches are now in Material 3 style.

## 0.8.9

- Updated Japanese, Russian & Chinese Simplified translations.

## 0.8.8

- Major internal changes on how apps are loaded & handled internally (This is the initial step toward Icon Pack support).
- Fixed shortcut launch sometimes causes crashes.
- Fixed App Options Menu not closing when back press.

## 0.8.7

- Major optimizations on how the new search system works.
- App & contact search results now load separately and a loading indicator is shown when any of them is still being loaded (this is done due remove the unneeded delay of showing app results because contact results take longer to load).
- Removed Search algorithm options.
- Migrated the translation center to [Crowdin](https://crowdin.com/project/yasan-launcher) from OneSky. All translations are now get added to the app instantly. This change adds partial support for Chinese Simplified, Japanese, Persian & Swedish.

## 0.8.6

- New Search screen UI with contact search support.
- Fixed Filled style being used as the default Buttons Box icon style.
- Changed all icons style to Rounded (from Filled).
- Adjusted rounded corner size on some UI components.
- Major optimizations on how the Search Screen functions internally.

## 0.8.5

- Fixed some UI issues due to the new design introduced on v0.8.4.

## 0.8.4

- Introducing Material 3 redesign with Material You (color palette) support.
- Removed the option to manually pick home components' color (will be replaced with a new & easier to use system soon).
- Removed the option to choose your AI system. This is done to decrease unneeded complexity of how the AI system works internally and should make all AI actions run faster.
- Removed the option to toggle cross-fade, always disabled now (until its fixed).
- Misc. image loading optimizations.
- Fixed YASAN Logo being distorted on some screens.
- Option descriptions now use a dot separator instead of a comma.
- Removed markdown styling on Changelog screen (will be replaced with a better system soon).

## 0.8.3

- App Hide button's description now changes based on whether Drawer is enabled or not.
- Fix app shortcuts icon not being loaded with the proper size for the device.
- Changelog text is now rendered properly (still not perfect, but better).
- Fixed drawer icon being shown when its disabled when buttons box position is on start/end/left/right of home box.

## 0.8.2

- Added the option to hide apps from Dashboard's Other Apps folder.
- Fixed billing client not initializing after the launcher is reopened from the background (resolves premium not being purchasable in some scenarios, please try again if you previously had issues).
- Fixed home title bars sometimes not being centered vertically.

## 0.8.1

- New option to disable Drawer! When disabled, any app that is not in a folder is put in an automatically updated folder called "Other Apps".
- New option to change the order of folders! You can access this option on: Options -> Dashboard -> Folders -> Up/Down buttons.
- Major fixes & optimizations on Premium Screen and how it handles its error states.
- Fixed About screen not showing the default data while fetching the latest data from the remote server.
- Fixed latest LiveInformation (social links etc.) not being saved in the app.
- Fixed About screen's developer segment not having a divider on the bottom.
- Removed Shop link from About screen.
- Added YASAN logo to About screen.
- New animations on the intro pages.

## 0.8.0

- Version naming system is back to semantic (X.Y.Z).
- Adjusted some version related UIs to work with semantic versioning properly.
- New font preview texts.
- Fix padding sizes on New Folder screen, App Pin screen, App Hide screen.
- Improved visibility toggle animations for some setting options.
- Some experimental internal icon loading features.

## 22.03-363

- Major changes on the Search screen's UI.
- Miscellaneous bug fixes & performance improvements.

## 22.03-DEV-362

- Updated to Compose v1.1.1.
- Fixed some paddings being too large due to changes on Compose v1.1.0+.

## 22.03-DEV-361

- Search screen's content is now on top (due to the keyboard issue in compose not being fixed after about a year).
- Apps position changes are now animated on Search (apps being added or removed is not animated yet).
- Migrated to YDK (YASAN Development Kit).

## 22.03-DEV-359/360

- Update to Compose 1.1.0 (and other Compose related dependencies).

## 22.03-DEV-358

- Fixed apps not being added to launcher when the launcher is not running (merged into stable 22.02-357).

## 22.02-357

- New Folder Styles! You can now customize how your apps are shown on the Dashboard. Your options are the grid (new) & list styles.
- Miscellaneous bug fixes.

## 22.02-DEV-356 (RC-1)

- Bottom sheets now have rounded corners similar to the rest of the launcher UI.
- Improved folder's grid layout (more visible on Tablets).
- Fix the launcher's icon being visible in itself.

## 22.02-DEV-355

- New Dashboard Folder style options! You can now choose between list & grid folder styles!
- Fixed crashes when there are concurrent database modifications happening.

## 22.02-DEV-354

- Moved Greeting toggle to the main Dashboard options screen.
- Added button descriptions to Dashboard options items.
- Fixed crashes on premium screen when prices fail to load (hotfix; merged into stable 22.01-353)

## 22.01-353

- Fixed crashes on premium screen when prices fail to load (hotfix).

## 22.02-DEV-352

- Fixed crashes on premium screen for some users (hotfix; merged into stable 22.01-351).

## 22.01-351

- Fixed crashes on premium screen for some users (hotfix).

## 22.01-350

- Custom folder icon support with 100+ icon options.
- Major app search algorithm improvements (including the ability to search apps by their acronym).
- Improved Dashboard Greetings functionality.
- Many major bug fixes & performance improvements.

## 22.01-DEV-349 (RC-4)

- Fix app options menu not closing after an app shortcut is used.

## 22.01-DEV-348 (RC-3)

- Fixed Search screen not closing after an app is launched.
- Misc. search optimizations.

## 22.01-DEV-347 (RC-2)

- Fixed crash when the launcher is being destroyed.

## 22.01-DEV-346 (RC-1)

- App search can now find apps based on their acronym (will be toggle-able later, now its always on).
- Major improvements on the basic app search algorithm.
- App package name search is now only done if there are no results found previously (and is enabled).
- Fixed Pride Night greetings not working.
- Fixed horizontal padding on Intro's app boost page.
- Fixed App icon placeholders on Search screen not having the correct shape.
- Fixed pagers causing crash on configuration change (most common crash currently).
- Fixed search results not being updated after apps are modified (app uninstall).
- Optimized Search screen.

## 22.01-DEV-345

- Major improvements on Dashboard's greeting system.
- 19 new greeting texts (most of them are very rare).
- Fix "App not found" text not having any padding on App Options Menu.

## 22.01-DEV-344

- Fix custom folder icon not changing when creating a new folder.
- Optimizations on how folder icons are handled.
- Minor optimizations on New Folder screen.

## 22.01-DEV-343

- Updated the folder icons (there are now 121 folder icons available).
- Fixed wallpaper palette generation warning always being visible (Merged to stable on 21.12-342).

## 21.12-342

- Fixed wallpaper palette generation warning always being visible.

## 22.01-DEV-340

- Custom folder icon support (currently supports 101 icons)
- The launcher picker pop up is now improved and will not open default app settings anymore.
- [EASTER EGG].

## 21.12-338

- App shortcut support.
- Improved App Options Menu for easier app management.
- App Options menu customization support.
- New Feedback screen.
- News support.
- Many bug fixes & performance improvements.

More information available on yasandev.medium.com

## 21.12-DEV-337 (RC-1)

- News support.
- Launching news or social links from About screen is now logged into Firebase.

## 21.12-DEV-336

- App shortcut launches now affect AI data (currently treated as the same AI event as launching an app normally).
- App shortcut launches are now logged into Firebase as events (does not contain what app was launched & still fully anonymous).
- Premium Pop-up is now converted into a bottom sheet (used to be a dialog) & its style is adjusted a bit.
- Fix bottom sheet navigation events not being logged into Firebase.
- Fix non-premium users being able to sometimes enable app pin for apps from App Pin options screen (only the switches are bugged and it does not affect the actual pin behavior).
- Premium features list style is adjusted.
- Removed 'Advanced App Options Menu' from premium features list.
- Optimizations on how AI events are recorded.
- Now when app hide on home or app pin are toggled for an app from App Options Menu and the other one is already enabled, a warning will show about app hide overriding app pin.
- Adjusted version information texts' layout on App Options Menu.

## 21.12-DEV-335

- Major Compose-related library updates.
- Now launching or closing any screen is logged into Firebase (fully anonymous as previous events & only used to learn how users use the launcher. An opt-out option might be added later).

## 21.12-DEV-333

- New App Options Menu screen that lets you fully customize it.
- The spacer below app shortcuts is now larger (6g from 2g).
- App shortcuts are now sorted by their rank.
- Sliders can now have a custom name for their min & max value.
- Sliders' value changes are now animated.
- Fix float sliders title font weight not matching integer slider title font weight.
- App Options is now called App Options Menu for clarity.

## 21.12-DEV-334

- New "Long Labels" option on App Options Menu.
- Fix crash when wallpaper drawable cannot be loaded due to reasons other than missing permissions.
- Improved the Switch title for Branding Footer on Dashboard Options.
- Fix App Options Menu crashing sometimes when trying to check if the app can be uninstalled or not.
- (Potentially) fix launcher crashing sometimes when trying to navigate back to the Home screen.
- Going back to home now always brings you back to the main Home screen and not the previously open page of Home Pager (Dashboard, Home & Drawer).

## 21.12-DEV-332

- App shortcut support!

Notes:

- Requires Android 7.1+.
- Requires the launcher to be the default home app.
- Potentially bugged in some scenarios, please report.

## 21.11-331

- Changelog data is now fetched from <https://github.com/yasandev/yasan-launcher-changelog>.

## 21.12-DEV-330

- Fix the launcher crashing sometimes on some devices when trying to load app icons [Merged to Stable].

## 21.12-DEV-328

- Fix installed text on Changelog screen.
- Added a spacer between Show Branding & Folders options on Dashboard Options screens.
- Dashboard branding is now enabled by default.
- Optimized how & when folders & app shortcuts are updated.
- Folder switches are now replaces with checkboxes on App Options.
- Added "Advanced App Options" to premium features list on Premium screen.
- New Feedback screen to easily create issues on <https://github.com/yasandev/yasan-launcher-issues> repository for bug reports and feature requests (please do not create issues until 21.12 is live as stable).

## 21.12-DEV-327

- Folders segment on App Options is now visible even if you have not created a folder yet.
- App Options footer spacer & padding are now increased.
- Fix multiples of an app being added to a folder if the folder was created from App Options.

## 21.12-DEV-326

- Fix App Options bottom spacer color.
- Apps clickable area on Drawer (Grid), Dashboard Folders, Search & Home is now rounded.
- Back buttons clickable area on Drawer & Dashboard is now rounded.
- If the other version of YASAN Launcher is installed the version information is now visible on Changelog screen.
- Apps version name & code is now visible on the bottom of App Options.

## 21.12-DEV-325

- Added App Pin switch to App Options (only available to Premium users).
- New "New Folder" button on App Options which opens the new folder screen and adds the app automatically on start.
- App Pin as a feature cannot be toggled anymore (its always enabled if you are a premium user).
- Fix drawer apps not being updated when an app is added/removed to/from a folder from App Options.
- Fix App Pin list items always using Rubik font.
- Fix App Pin list items paddings.

## 21.12-DEV-324

- Added App Hide options to App Options (only available to Premium users).
- Added Folder options to App Options to easily add/remove apps to/from folders.
- Long clicking Dashboard shortcuts now opens App Options.
- App Hide as a feature cannot be toggled anymore (its always enabled if you are a premium user).
- Some adjustments on when folder & dashboard shortcut data is refreshed.

## 21.12-DEV-323

- Fixed warning UI being blank somehow (previously used on Color picker screen).
- Now if the launcher is not set as the default launcher a warning will be shown on the main options screen.
- Segment titles on Color picker screen no longer have the extra spacer.
- Removed Advanced options screen and the "Change default home app" button is now moved to the main options screen for easier access.
- Added the option to show YASAN Launcher logo & version name on the bottom of Dashboard (disabled by default).
- Update to Compose v1.0.5 (from v1.0.4).

## 21.12-DEV-322

- Update Coil to v1.4.0 from v1.3.2 (~~fixes cross-fade bug?~~).
- Changelog data is now fetched from <https://github.com/yasandev/yasan-launcher-changelog>.
- Fix global events not being triggered if the new event is the same as the previous event.
- Major improvements & optimizations on how home button clicks are handled (fixes many weird behaviors).
- Fix long clicking apps on Search launching the app information screen instead of opening the app options bottom sheet.
- Add click labels for Buttons Box (accessibility).
- Fix some image content descriptions (accessibility).
- Use cross-fade for loading YASAN & YASAN Launcher logos.

## 21.12-DEV-321

- "App Icons" slider title is now renamed to "App Count" on Apps Box Options screen (included in 21.11-320 stable release).
- Optimized how apps list on Drawer is updated (applies only to the list view).

## 21.11-DEV-319 (RC-2)

- Optimized how New/Edit folder screen handles different folder modification events which fixes the duplicate message & multiple navigation actions when the modification is successful bugs (this introduces a new global event queue system to the whole launcher system that might be buggy in some heavy use cases, it will only ship to 21.11 if there are no issues reported).
- New/Edit folder screen messages now show as Toasts and not SnackBars as they are less annoying and can be shown for shorter durations easily (Is going to be replaced with a custom snackbar style soon).
- Folder apps are no longer excluded from Drawer by default.

## 21.11-DEV-318 (RC-1)

- App icons cross-fade animation can now be toggled on and off from Look & Feel options screen.
- Changelog text size decreased to 14sp (from 16sp).

## 21.11-DEV-317

- New "Icon Style" option for Buttons box which lets the user choose from 5 different icon styles.
- App options dialog is now shown as a bottom sheet.
- Dashboard Greeting's weekday text now properly follows the devices default locale.
- Remove widget support for 21.11 release.
- Fix Layout segment title disappearing if icons are disabled on Drawer Options screen.
- Added App Icon size preview to Apps Box Options screen.
- Added App Icon size preview to Drawer Options screen.
- Added App Icon size preview to Search Options screen.
- Optimize how the selected font family is fetched on different screens.
- Improve the icon placeholder highlight color.
- Search Options are now divided into two segments for easier use.
- "Icons" segment title is now renamed to "App Icons" on Drawer Options screen.
- "App Icons" switch title is now renamed to "Enabled" on Drawer Options screen.
- "App Label" segment title is now renamed to "App Labels" on Drawer Options screen.
- "Icons" segment title is now renamed to "App Icons" on Apps Box Options screen.
- "Apps" slider title is now renamed to "App Count" on Apps Box Options screen.

## 21.11-DEV-316

- Compose 1.0.4.
- Kotlin 1.5.31.
- Major app icon loading optimizations which greatly reduces the initial loading time & uses less memory.
- App icons now show a placeholder while being loaded.
- App icons now always have a cross-fade effect when being loaded.
- Fix AppWidgetHost memory leak (hopefully).
- Fix Drawer icon size preview not matching the icon sizes on Drawer.
- Adjusted app icon paddings.

## 21.11-DEV-315

- The exact app version is now shown on the Changelog screen & the Changelog buttons description.
- Fix widget list text color being black on night/dark mode.
- Fix changelog text color being black on night/dark mode.
- Fix Billing Client memory leak.
- Removed broken widget preview images.

## 21.11-DEV-314

- Now you can read the app changelog for both release channels on the new Changelog screen (it currently shows the raw markdown file without formatting but it will be improved soon).
- Added an Uninstall button on App Details Dialog which is only shown if the app can be uninstalled (Currently looks a bit weird but the whole App Details Dialog UI is going to get changed anyways).
- Improved default Home colors.
- Fixed Pride options screen having an invalid name.
- Added lots of missing button descriptions.
- Removed AI IQ & AI Performance user properties.
- Build time text on the About screen is now properly formatted to be easily readable.
- Misc. code quality improvements.

## 21.11-DEV-313

- The unstable/developer channel is now renamed to DEV since NEXT can cause confusion.
- Widget picker list (still very wip).

## 21.11-NEXT-312

- Kotlin 1.5.30.
- Compose 1.0.3.
- Small bug fixes & performance improvements.
- Fix some invalid icon content descriptions.
- Initial developer level Widget support which also includes a new set of buttons on the bottom of Dashboard.

## 21.11-NEXT-311

- Segment titles now have extra vertical spacing on top to make everything more separated and cleaner.
- Segment titles parent text is now on shown on top of title.
- Fix Icon Size Preview on Apps Drawer Options not rounding the corners of the item below it.
- Update all legacy sliders to optimize performance.
- Update Compose Accompanist to 0.19.0 (mainly effects view pagers like Home & Intro).


## 21.11-329

- Fix the launcher crashing sometimes on some devices when trying to load app icons.

## 21.11-320

- Major bug fixes & performance improvements across the board.
- New changelog screen.
- New app options bottom sheet.
- New "Uninstall" app option.
- Cross-fade support for app icons.
- Option screens have received many adjustments to be easier to understand.

## 21.10-309

- Choose different dark & light colors for all home elements.
- Exclude folder apps from being shown on Drawer.
- UI/UX improvements.
- Premium-related bug fixes.
- Misc. bug fixes & performance updates.

## 21.10-NEXT-308 (RC-2)

- Fix premium status update system being too strict causing premium to be disabled temporarily for premium users.
- Some optimizations on option sliders.

## 21.10-NEXT-307 (RC-1)

- Changed Color Picker Button's style.
- Changed Home Alignment Picker's style.
- Decreased divider width size (1dp from 2dp).
- Some optimizations on Intro & About screens.
- Start & End strings are now replaced with "Left" & "Right" as LTR is only supported yet.

## 21.10-NEXT-306

- The option to exclude folder apps from being shown on Drawer (Enabled by default).
- Optimized how apps are loaded into Drawer.
- Fixed typo in the message shown when Live Information fails to load on About screen.
- Default Home app icon size set to 72 from 64.
- Apps Box options screen is now more organized & Row/Column option is improved.

## 21.10-NEXT-305

- Improved the title text for dark & light color picker screens.
- Improved palette generation configuration.

## 21.10-NEXT-304

- The option to pick individual custom colors for light & dark UI modes.

## 21.10-NEXT-303

- Fix crash when apps are being loaded from system & the device is shutting down in the same time.
- Compose 1.0.2.
- Compile SDK set to SDK 31.

## 21.10-NEXT-302

- Fix crash when loading AI performance data if you previously had a very old version of the launcher installed.
- Fix "Icon" & "Icons" strings not being capitalized.
- Fix Premium screen crash when Sku details list is null.

## 21.09-301

- Fix crash when loading AI performance data if you previously had a very old version of the launcher installed.

## 21.09-300

- The Next Generation of YASAN Launcher is here!

## 21.09-NEXT-288 (FINAL)

- Fix crash when no activity could be launched for setting screens.
- Simplify build time stamp on About Screen.

## 21.09-NEXT-287 (RC-1)

- Full intro functionality.
- Removed some DEV tools.
- Disabled all image loading cross-fade animations due to being bugged in Coil.
- Fix primary and secondary colors being flipped in day/night themes for some elements.
- AI IQ & AI Performance are now a user property in analytics.

## 21.09-NEXT-286

- Navigation animations reverted back to simple fade animations due to slide animations not looking right.
- Vertical swipes on Home are now a little bit more sensitive (minimum drag amount decreased to 65 from 75).
- Improved analytical data collection (Home, Dashboard & Drawer screens being opened are now recorded as events & premium product key is a user property).

## 21.09-NEXT-285

- Compose 1.0.1.
- Navigation animation is now a horizontal slide but if the target screen is Home it is a simple fade animation.
- All images are now loaded using Coil Compose & have crossfade effect when being loaded.
- Force max one lines for folder names on Dashboard (If the folder name is long, it is going to be ellipsed).
- Fix Home gestures button description.
- Add App Pin button description.
- Improve Home Box button description.

## 21.09-NEXT-284

- Fix folder state not being updated in the proper order on Folder creation/edit screen.
- Fix crash after deleting a folder.

## 21.09-NEXT-283

- New Intro screen support. It currently only lets you boost some of your apps' AI score on the first launch.
- Compose 1.0.0 (Stable).
- Fix the bug where the initial value of apps status in folders edit screen was incorrect.
- Fix how back stack was handled internally which caused crashes with the latest version of Compose Navigation.
- Remove fake loading delay when opening folder information screen.
- Disable RTL support (layouts no longer flip horizontally when the device language is RTL).
- Disable folder edit's click ripple effect (should be fixed soon).
- Folder edit icon replaced from "Edit" to "ChevronRight".
- Folder edit clickable area is now the whole row instead of the icon only on Dashboard.
- A simple cross-fade animation is automatically added to all navigation actions due to updated Compose libraries.
- [TEMP] Android MinSDK set to 24 (from 23) due to a Compose issue.

## 21.08-NEXT-282

- ~~Fix the bug where the initial value of apps status in folders edit screen was incorrect.~~
- Fix layout corners on Premium screen when premium is enabled.
- Fix About screen's live developer information not being able to show failures.
- Home swipe actions are 3 times less sensitive now.

## 21.08-NEXT-281

- App pin support (works like the legacy app pin feature, will be replaced with a much more sophisticated system in next releases).
- Improved Premium Dialog style.
- Fix border color buttons not being named properly.
- Fix color picker screen showing "?" for border colors.
- Fix color picker screen not having the correct default value for border colors.
- Fix crash on drawer (hopefully).
- Fix switches description text being limited to one line.
- Fix switches not having the proper amount of padding when the description is long.
- Remove Premium related event trackers (bugged, will be replaced later).
- Remove Home Drag option (now always on).
- Add descriptions to Search options Switches.
- EASTER EGG #1.

## 21.08-NEXT-280

- Border width & color support for Apps Box & Buttons box.
- Fix options having non existent children list.
- Remove Fast Scroll feature.
- Fix Layout segment title on Drawer options not being always visible.
- Segment titles can now show the segment's parent.
- New edit button on folders to easily edit them without having to open options screen.

## 21.08-NEXT-279

- Previews now round corners of the content below them when expanded.
- Updated to Compose 1.0.0-rc02
- Fix Premium screen always showing the active premium screen.
- Fix rounded corners on Premium screen when Premium is disabled.

## 21.08-NEXT-278

- Fix more crashes related to loading icons.
- NEXT is now published in the beta channel instead of internal. It is still possible that some rare updates go to internal only.

## 21.08-NEXT-277

- Migrated to non-legacy UI elements on Search options.
- Fix crash when trying to load an icon for an uninstalled app.
- Fix crash when loading first label characters when app list is empty.

## 21.08-NEXT-274

- New improved floating page style on all screens.
- New icon size preview on Drawer options.
- Premium features list no longer always visible on Premium screen.
- Fixed the main options screen not recycling properly.
- Moved Fast Scroll switch to List options.
- Fix New Folder screen's title being "New Folder Options".
- Added a larger spacer below Dashboard items.

## 21.08-NEXT-273

- Add App Hide to Premium features list on Premium screen.
- Premium features list is now always visible on Premium screen.
- Cleaned up Drawer options screen to make it clearer.
- Fix Home previews letting user open app options dialog on long click.
- Home previews now have rounded corners once expanded.
- Home previews expanded state is now saved on device and restored properly.

## 21.08-NEXT-272

- Fix crash when trying to find the main user's serial.

## 21.08-NEXT-271

- Improved Work/Managed profile support.
- Improved icon loading system.
- Now whenever the launcher is restarted, it will go back to Home automatically.

## 21.08-NEXT-269

- New app loading system which supports Work/Managed Profiles.
- Work/Managed apps are now shown on Dashboard as a folder and not visible anywhere else.

## 21.08-NEXT-268

- Fix Home previews' background not showing wallpaper.
- Remove Bottom Branding from Dashboard.
- Remove Dark mode options from Look & Feel options screen.
- Convert Font options into a radio group instead of the legacy drop down menu.
- Remove unneeded divider on Search screen.
- Radio groups can now sort their items alphabetically if needed.
- New Gender queer, Gender fluid, Pan-sexual, Agender, Non-binary, Aromantic & Lesbian Pride flags.
- Renamed "LGBT" flag to "Rainbow Pride".

## 21.08-NEXT-267

- Fixed "No Results" text on Search not use the selected font.
- Improved Search screen style that does not cover all of the screen & has proper animations.
- If an app is launched from Search, Search screen will be closed automatically in the background.
- Fixed Color picker having x2 margin size.

## 21.08-NEXT-266

- New floating page style on all screens except Home.
- Fixed YASAN logo not being shown properly (by using Coil).
- Default home margin size set to 1.5 (down from 4.5).

## 21.08-NEXT-265

- "Loading Apps" indictors color is now automatically selected based on apps box background color.
- Added the option to select the amount each corner of Apps box & Buttons box should be rounded.
- Removed wallpaper modes.
- Removed wallpaper options screen.
- Removed vertical scroll option.
- Color picker screen now handles missing storage permission properly & shows a text if needed.
- Color picker screen now shows a text if it is unable to create a color palette using the wallpaper.
- New "Reset to Default" button on Color picker screen.
- Support custom folder app icon size.
- Expand notification on swipe down.
- Launch Search screen on swipe up.
- Some new configurations set on the Manifest.

## 21.08-NEXT-263

- Color picker now shows 6 recent used colors.
- Remove buttons box border.

## 21.08-NEXT-262

- New advanced color picker screen.
- Custom color support for Frame background, Frame margin background, Apps box background, Buttons box background & buttons tint.
- Improved event tracking for Premium related events.
- Some small UI changes to make some options clearer.

## 21.08-NEXT-261

- Fix the ripple effect style on Shop & website icons on About screen.
- Simplified how the version name is shown on the Bottom Branding banner. It also now shows a build version and time of the build only on the About screen.
- Switches can now show a description below the title.
- New Pride options for Dashboard which currently lets you show a Pride flag on Dashboard (Currently supports LGBT, Bisexual, Asexual & Trans)
- New System Settings button on the options screen.
- New Advanced options screen which only lets you easily change the default home for now.
- Fix Search options screen title being "Search".
- New "Folders" segment title on Folder options screen.

## 21.08-NEXT-260

- New Shortcut settings option on Dashboard options. It currently lets you choose how your shortcuts are sorted.
- Dashboard clock is now always shown if Greeting is disabled.
- Dashboard clock text color is now the primary color (YASAN Blue) when the time is 11:11.
- Dashboard clock is now visible below the greeting text when a Greeting text is active.
- Fix the "crash" when the system is being shut down (dead) and apps are being loaded in the same time.
- Fix Dialog width size bug on Compose 1.0.0-rc1.
- Fix Premium information on Premium header on the main options screen not use the selected font.
- Fix Drawer item's sorting change with a delay when Drawer was opened.
- New Premium-Only Feature banner added. Currently only used on App Hide screen.

## 21.08-NEXT-259

- Improve Dashboard spacer sizes.
- ~~Added a progress bar when the shortcuts are loading.~~
- Compose version 1.0.0-rc01 ~~(should fix the keyboard issue on Search)~~.

## 21.07-NEXT-258

- Close app options pop up when the app information screen is launched.
- Fix ripple effect style for sliders.
- App options dialog now shows the app icon.
- Versions no longer have a special version name.
- Drawer App icons in grid mode now have more space around them on tablet devices.
- Remove Fast Scroll support from Grid Drawer.
- Option button's description is now a single line.
- App Hide is now locked for non-premium users (The premium dialog is a placeholder).
- The spacer between Dashboard items is now smaller.
