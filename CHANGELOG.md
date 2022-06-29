# Changelog

## 3.5.0 (2022/04/04)

* Fix HashMyFiles and Wget download links (#251)
* Bump github.com/stretchr/testify from 1.7.0 to 1.7.1 (#245)
* Bump github.com/mitchellh/mapstructure from 1.4.2 to 1.4.3 (#232)
* Bump github.com/rs/zerolog from 1.26.0 to 1.26.1 (#234)
* Bump github.com/josephspurrier/goversioninfo from 1.3.0 to 1.4.0 (#237)

## 3.4.0 (2021/11/21)

* Go 1.17 (#230)
* Don't fail on corrupt portapp-prev (#217)
* Bump github.com/go-ole/go-ole from 1.2.5 to 1.2.6 (#225)
* Bump github.com/mitchellh/mapstructure from 1.4.1 to 1.4.2 (#223)
* Bump github.com/rs/zerolog from 1.23.0 to 1.26.0 (#219 #228)

## 3.3.1 (2021/08/23)

* Update `golang.org/x/sys`
* Use `exec.Command.Run`
* Bump github.com/josephspurrier/goversioninfo from 1.2.0 to 1.3.0 (#215)
* Bump codecov/codecov-action from 1 to 2
* Bump github.com/rs/zerolog from 1.20.0 to 1.22.0 (#199 #202)

## 3.3.0 (2021/03/04)

* Go 1.16

## 3.2.2 (2021/02/25)

* Update 7zip extra download link

## 3.2.1 (2021/02/15)

* Revert 7zip extra download link

## 3.2.0 (2021/02/15)

* Use default GOPROXY value
* Update 7zip extra download link
* Bump github.com/stretchr/testify from 1.6.1 to 1.7.0 (#170)
* Bump github.com/mitchellh/mapstructure from 1.4.0 to 1.4.1 (#169)
* Bump github.com/go-ole/go-ole from 1.2.4 to 1.2.5 (#168)

## 3.1.0 (2020/12/13)

* Add `Config` func to return global app configuration
* Add `ElectronAppPath` func to return the app electron path
* Add `ErrorBoxLog` and `FatalBoxLog` funcs

## 3.0.3 (2020/12/03)

* Fix command exec

## 3.0.2 (2020/12/03)

* Fix nil pointer on exec

## 3.0.1 (2020/12/03)

* Fix Electron asar target

## 3.0.0 (2020/12/02)

* Switch to GitHub Actions (#161)
* Fix build common
* Remove travis-wait-enhanced
* Add go version and go env targets
* Remove syscall (#162)
* Add some tests
* Allow to disable UPX compression
* Go 1.15.5
* Bump github.com/rs/zerolog from 1.19.0 to 1.20.0 (#150)
* Bump github.com/mitchellh/mapstructure from 1.3.3 to 1.4.0 (#160)
* Bump gopkg.in/yaml.v2 from 2.3.0 to 2.4.0 (#158)

## 2.6.0 (2020/08/18)

* Set InnoSetup `ArchitecturesAllowed`
* Fix rcedit macrodef
* goversioninfo 1.2.0
* Innoextract 1.9

## 2.5.0 (2020/08/03)

* Fix RootPath resolution (#122)
* Add `msi` build type
* Fix `extractmsi` macrodef
* Allow to open a reg key
* Update deps

## 2.4.4 (2020/05/29)

* Ant 1.10.8
* travis-wait-enhanced 1.2.0
* UPX 3.96

## 2.4.3 (2020/05/29)

* Follow redirect with cURL

## 2.4.2 (2020/05/29)

* Fix OpenJDK link

## 2.4.1 (2020/05/28)

* OpenJDK 11.0.7
* Force goproxy

## 2.4.0 (2020/05/28)

* Save previous metadata in `portapp-prev.json`
* Update deps

## 2.3.0 (2020/05/19)

* Allow to include custom Run config for Setup
* Update deps

## 2.2.4 (2020/04/28)

* Strip debugging info

## 2.2.3 (2020/04/28)

* Build notifications only from portapps
* Code cleanup
* Update deps

## 2.2.2 (2020/04/25)

* Allow to set default registry key value

## 2.2.1 (2020/04/25)

* Do not remove the last exported reg

## 2.2.0 (2020/04/25)

* Check reg key exists before export (portapps/hlsw-portable#8)
* Add backup retention for exported reg keys
* Load lessmsi
* Update deps

## 2.1.2 (2020/04/13)

* Fix "No Go source files" behavior
* Coding style

## 2.1.1 (2020/04/13)

* Fix logger

## 2.1.0 (2020/04/13)

* Move lib to `pkg` folder
* Review logger implementation

## 2.0.5 (2020/04/12)

* Fix ANT release build

## 2.0.4 (2020/04/12)

* Fix Travis build

## 2.0.3 (2020/04/12)

* Build output more verbose
* Set `core.dir` on Travis

## 2.0.2 (2020/04/11)

* Bring back GOPROXY
* Fix Travis import

## 2.0.1 (2020/04/09)

* GOPROXY direct

## 2.0.0 (2020/04/09)

* Add `disable_log` config option (#92)
* Review logger implementation
* Go 1.13.10
* Refactor init
* Add `registry.Delete` function
* Fix Apache ANT and ANT contrib download links
* Update deps

## 1.32.0 (2020/03/26)

* Fix Apache ANT and ANT contrib download links
* Update deps

## 1.31.0 (2019/12/13)

* Asar 2.0.3
* travis-wait-enhanced 1.1.0
* Add `Cleanup` function

## 1.30.1 (2019/11/07)

* Fix setup release

## 1.30.0 (2019/11/06)

* Move `finalize` call
* Allow to use a custom ISS template through `papp.iss` prop
* Factorise packaging
* Display Windows OS version in logs
* Fix `win.GetVersion` function
* Add `AppendToFile` and `FileContains` functions

## 1.29.0 (2019/11/05)

* Asar 2.0.1
* InnoSetup 6.0.3
* Rcedit 1.1.1
* travis-wait-enhanced 1.0.0
* Fix InnoSetup license dialog
* Update deps

## 1.28.0 (2019/10/01)

* Allow to extract app asar

## 1.27.0 (2019/10/01)

* Go 1.12.10
* Tools build constraint
* Force `GO111MODULE` and use `GOPROXY`
* `app.release` now required
* Fix 7zip download link
* Innoextract 1.8

## 1.26.1 (2019/09/05)

* Update default UPX args
* Ant 1.10.7
* Add lessmsi lib
* Split libs in separate files

## 1.26.0 (2019/08/21)

* Add `Replace` and `Is64Arch` functions

## 1.25.0 (2019/08/03)

* Allow to (not) include original artifact
* Add [travis-wait-enhanced](https://github.com/crazy-max/travis-wait-enhanced)
* Disable InnoSetup compression progress
* Allow to override InnoSetup compression
* Use current generated build files for InnoSetup source
* Allow to override 7z and UPX compression level
* Clean more files on update (InnoSetup)
* Disable default ANT excludes
* Add download verbosity
* Use syscall
* Disable go build verbosity

## 1.24.1 (2019/05/16)

* Error while changing `app_path` (Issue #35)

## 1.24.0 (2019/05/15)

* Add "Notice of Non-Affiliation and Disclaimer" setup wizard page (Issue #33)
* Switch to unicode release of InnoSetup
* Set empty appPath value by default in configuration

## 1.23.0 (2019/05/07)

* Allow to choose application binaries path (Issue #28)
* Log app info
* Handle `portapp.json` through app object
* Add `DownloadFile` function

## 1.22.2 (2019/04/28)

* Make the path to the file containing `userData` for Electron configurable

## 1.22.1 (2019/04/18)

* Add `RefreshEnv` and `SetPermEnv` functions
* Switch to OpenJDK 11.0.2
* Add wget build tool dependency
* Update deps

## 1.22.0 (2019/04/15)

* Go 1.12
* Update deps

## 1.21.0 (2019/03/26)

* Handle placeholders for environment variables in configuration
* Add `Locale` function

## 1.20.3 (2019/03/17)

* Fail if no replacements found

## 1.20.2 (2019/03/09)

* Update setup image
* Add `RoamingPath` and `StartMenuPath` utility functions

## 1.20.1 (2019/03/08)

* Add ability to set environment variables from config
* Set Portapps version through Windows FileVersion property
* Throw error if command fails
* Coding style

## 1.20.0 (2019/03/08)

* Move logs to log folder
* Switch to [zerolog](https://github.com/rs/zerolog)
* Fix error while using registry pkg
* Update 7zip and asar libs
* Update goversion
* Refactoring

## 1.19.2 (2019/03/06)

* Omit app config if empty
* Check underlying app config value

## 1.19.1 (2019/03/06)

* Review and fix mutex
* Display message box on fatal error
* Display message box if main process is not found
* Add Portapps core version in `portapp.json`

## 1.19.0 (2019/03/05)

* Implement global configuration file (Issue #12)
* Add Windows MsgBox helpers
* Reorganize package
* Update deps

## 1.18.0 (2019/02/17)

* Add checksums file to releases (Issue #11)
* Switch to TravisCI

## 1.17.0 (2019/01/08)

* Add `CreateMutex` function

## 1.16.1 (2018/11/16)

* Fix error while compressing using UPX

## 1.16 (2018/10/26)

* Allow to enable CGO
* Review `CreateShortcut` function
* Add functions `Exists`, `IsDirEmpty`, `RawWinver`, `ReplaceByPrefix`, `WriteToFile`
* Add build type single

## 1.15 (2018/10/03)

* Add functions `CreateShortcut`, `SetFileAttributes`, `CopyFile`, `CopyFolder`, `RemoveContents`

## 1.14 (2018/09/30)

* Update InnoSetup to 5.6.1
* Update UPX to 3.95

## 1.13 (2018/09/29)

* `RegAdd` function added to create a registry key
* Allow to pass overwrite option while extracting files (default `-aoa`)
* Remove nsis-muarch build mode (use archive mode instead)

## 1.12 (2018/09/19)

* Assume Yes on all queries while extracting files
* Add go.sum

## 1.11 (2018/09/07)

* Go 1.11
* Use [go mod](https://golang.org/cmd/go/#hdr-Module_maintenance) instead of `dep`
* Fix asar lib version
* Disable strict-ssl on asar
* Update deps

## 1.10 (2018/04/28)

* Duplicated prepare target
* Update 7zip download link

## 1.9 (2018/03/13)

* Update deps
* Add QuickExecCmd function
* Add SetConsoleTitle function to set window console title
* Exclude version.dat from deletion
* Allow to use custom version for electron apps
* Add a check while creating folders
* ldflags can be customized

## 1.8 (2018/02/12)

* Add portapp.json file
* Uncheck run app in setup
* Mutualise release.app task
* App version not set in executable
* New artifact target (atf.win3264) for multi arch apps
* Move ia32/x64 to win32/win64 for arch def
* Add file creation, format unix / windows path
* Remove nupkg file
* Remove unnecessary files if not in debug mode

## 1.7 (2018/02/08)

* Ability to pass custom args to the portable process
* Update to rcedit 1.0.0
* Remove appasar from global electron build
* Add setelectronuserdata macro and load.lib.asar target
* Allow multi replacements in app.asar
* Ability to process a custom asar file

## 1.6 (2018/01/13)

* Replace userData in electron.asar for electron build type

## 1.5 (2017/12/14)

* Remove atf.original from untouched releases (can be found in the untouched repo)
* Add output type (7z or exe)

## 1.4 (2017/11/24)

* Disable UPX in debug mode
* Mutualize InnoSetup tpls
* Add NSIS Multi arch type
* Add prepare and finalize targets

## 1.3 (2017/11/23)

* Add untouched type

## 1.2 (2017/11/21)

* Coding style
* Add type archive, electron and innosetup
* Add debug mode
* Move app to a subfolder
* Manage registry keys

## 1.1 (2017/11/19)

* Disable basepath
* Fix execution stub resolution
* Grab LICENSE file from app repository
* Add CHANGELOG to release archive / setup
* Check artifact arch
* Setup default dir to C:\portapps\app
* Clear default values

## 1.0 (2017/11/16)

* Initial version
