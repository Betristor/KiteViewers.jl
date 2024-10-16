# Changelog

### KiteViewers v0.4.18 - 2024-10-16
#### Changed
- bump KiteUtils to 0.8

### KiteViewers v0.4.17 - 2024-08-25
#### Changed
- replaced Plots with ControlPlots in Project.toml and the examples
- deleted obsolete files, e.g. plots.jl
- fix examples
#### Added
- add support for 3-line kite
- add WAIVER from Delft University to README.md
- add menu.jl
#### Fixed
- fix tests

### KiteViewers v0.4.16 - 2024-07-28
- bugfix in function clear_viewer(), rename parameter `stop` to `stop_`

### KiteViewers v0.4.15 - 2024-07-28
#### Changed
- add optional, boolean parameter `stop` to the function clear_viewer()
- update KiteUtils to 0.7
- add example show_messages.jl that receives html messages
- fix the older examples

### KiteViewers v0.4.14 - 2024-07-15
#### Changed
- upgrade to GLMakie 0.10
- improve example reelout.jl

### KiteViewers v0.4.13 - 2024-07-08
#### Changed
- fix pre-compilation on Ubuntu 24.04
- replace `test_sterring.jl` with `test_parking.jl`
- fix tests
- smaller font size on Windows

### KiteViewers v0.4.12 - 2024-04-30
#### Added
- add menu_project for loading, saving and editing projects

### KiteViewers v0.4.11 - 2024-04-05
#### Added
- add menu time_lapse for changing the simulation/ replay speed
- add field `mod_text` to Viewer3D; it defines the quotient of the update rate and the text update rate
- add textbox `t_sim` to enter the simulation time

### KiteViewers v0.4.10 - 2024-03-30
#### Fixed
- fixed bug that caused problems with displaying tethers with more than 6 segments

#### Added
- the function Viewer3D() has now the optional parameter `menus=true`, if passed it shows the menus, otherwise not



