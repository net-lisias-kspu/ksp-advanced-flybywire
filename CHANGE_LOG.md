KSP Advanced Fly-By-Wire :: Change Log

* 2016-0422: 1.7a-beta (nlight) for KSP 1.1
	+ Updated for KSP 1.1
	+ (Beta release! Please report any issues.)
* 2016-0220: 1.6.2 (nlight) for KSP 1.0.5
	+ Fixed bad wheel throttle inputs causing unintended rover acceleration
		- Updated for KSP 1.0.5
		- Fixed WSAD controls not working with SAS off (fix by ddaf)
		- Updated bundled Toolbar mod
		- Re-implemented SAS override (by ddaf)
		- Fixed the disappearing SDL controller config (by DeamonSix)
		- Fixed a bug where SDL would identify the "centered" position as a button (by badpandabear)
		- A big thank you to all contributors and thanks to all users for waiting so long for this update \o/
		- This patch brought to you by ddaf
		- Fixed SAS being enabled when it shouldn't
		- The above change also fixed EVA movement related bugs
		- DirectX11- support has temporarily been disabled until the lag issues are solved
		- (Windows) Added support for DirectX11, should fix all missing controller issues
		- Fixed the EVA/ vessel change bug
		- Fixed a bug where staging during time-warp caused vessel parts to disappear
		- Fixed other time-warp related bugs
		- Fixed the throttle cut/ max throttle issue
		- Better default sensitivity settings
		- Fixed several other bugs
		- Now bundling blizzy's Toolbar 1.7.8
		- Hopefully fully adapted to 0.90 changes
		- SAS should work fine in all cases now
		- Negative versions of Yaw, Pitch, Roll, X, Y, Z are back
		- Fixed an issue with the mod breaking SAS
		- Support for KSP 0.90
		- Invert option is now per binding instead of per axis (thanks to ddaf!)
		- New feature 'IVA Look Window' (again, thanks to ddaf)
		- Fixed a rare NRE in the GUI
		- KSP-AVC support for the Linux release
		- Due to the config file changes, you will have to re- create your configuration
		- EVA!
			- EVA Jetpack", "EVA Interact", "EVA Jump", "EVA Plant Flag", "EVA AutoRun" have been added
		- Translation controls now work in EVA
		- Camera rotation now works in Map mode and IVA mode
		- Precision mode now works properly
	+ Everything in this update was generously contributed by ddaf (https://github.com/ddaf)
	+ I am very impressed by the work you did on this, thank you so much!
			- Fixed the wheel throttle bugs
			- Added a new "Brakes (Hold)" binding, renamed "Brakes" to "Brakes (Toggle)"
			- Fixed an issue where some axis combos wouldn't work
			- New options in controller configuration to set dead-zones from the GUI
			- Added "Quadratic (Inverted)" interpolation option
			- New controller test tool
			- Throttle and wheel throttle now reset to zero when you change vessels
			- Fixed the input locks bug
			- Fixed a bug where changing vessels mid-flight would result in AFBW controlling the old vessel
			- Fixed a bug where if KSP's working directory was not configured correctly the mod wouldn't find its config file
			- Merged Vitor Boschi's axis mapping fix
			- Toolbar button now closes the UI if it's already open
			- Added explicit "Save configuration" button to the main screen
			- Fixed input control locks for the new preset editor
			- Support for KSP-AVC
			- New preset editor
			- Many small GUI improvements
			- Now using KSP skin by default, option to revert to the old one
			- Updated toolbar to 1.7.7
			- KSP 0.25 support
			- Fixed misinterpreted controller hat inputs
			- Fixed issue with FAR where FAR's dynamic control adjustment would get overridden
			- Fixed trim issues
			- Added wheel throttle and wheel steer
			- Fixed a bug where throttle wouldn't go below 50%
			- Support for controller hats both as axes and buttons (new "Treat hats as buttons" config option)
			- Fixed SDL plug and play
			- Fixed a preset editor bug where if time is slowed down (e.g. by using the TimeScale mod), it was not possible to change bindings
			- General optimization
			- Breaks the configuration XML, you will need to recreate your presets.
			- Fixed the issues with time warp
			- B9 Aerospace now supported for 32-bit builds
			- Added negative versions of Yaw, Pitch, Roll, X, Y and Z
			- SDL2.dll wasn't always recognized to exist
