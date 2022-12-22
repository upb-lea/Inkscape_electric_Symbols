# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
 - Add electrolyth capacitor, PWM source
 - Add fan, BNC socket, inductor and capacitor drawings
 - Add coaxial cable
### Changed
 - Distance for isolated block symbols in distance-lines were not the same

## [1.3.0] - 2022-06-30
### Added
 - Add source / load
 - Add power analyzer
 - Components top-view (IC's, connectors)
 - Add flip-flop
 - Add control circuit symbols (various sum/subtract symbols)
 - Add light bulb
 - Add alternative resistor symbols
 
### Changed
 - Update scope
 - Update impedance analyzer
 - Minor changes to the examples

### Bugfixes
 - #5 was not fully fixed for colored arrows
 - Fix multiple connection lines in capacitor elements
 

## [1.2.3] - 2021-12-14
### Added
- add circles
- add symbols (battery storage, house)
- add symbol to extend wires
- add circuit board components
- add examples so readme.md
- add LAN-connector, USB-C, Notebook, 3D-Scope
- add Flyback converter
- add wind, thermometer

### Bugfixes
- #5: Marker Color from arrows chan not be changed

## [1.2.2] - 2021-09-17
### Added
- add DD-transformer
- add IGBT with parallel capacitance
- add BH-curve for magnetic materials
- add Multiplexer, Division-symbol
### Changed
- fix #3: Buck-Boost-Converter shows Buck-Converter

## [1.2.1] - 2021-05-25
### Added
- SMD housings
- add mini-xy-graph
- add test circuits: double-pulse test
### Changed
- fix #2: Wrong direktion of diodes in 3L converter

## [1.2.0] - 2021-01-31
### Added
- add parasitic capacitors to MOSFET components
- add topologies: LLC, PSFB, DAB
- add CHANGELOG.md
- add topologies: buck, boost, buck-boost
- add drawings: thermal heating of D2PACK with thermal vias

### Changed
- update reamde: update getting started section, add changelog to readme
- Releases now include the notes from the changelog-file

### Removed
- remove Inscape_Symbols_ISO60617.svg due to it is no longer maintained by this project. All symbols from this library can be found in Inkscape_Symbols_All.svg

## [1.1.0] - 2021-01-13
### Added
- magnetic circuits
- transformations: dq, abc, alpha-beta
- symbols: integrator, lookup-table, driver, I- P- PI-control, oscillators
- earth symbols
- greek symbols
- AC voltage source
- LICENSE
- drawing symbols: impedance analyser, scope, PV, server, motor, SD-card, car, wallbox, PC
- spark gap
- block symbols: add isolated variants of AC/DC, DC/AC, DC/DC converters

### Changed
- fix readme instructions
- change designators to italic
- update example-gif grafic
- fix phi sign
- fix MOSFETs body diode (line too short)
- fix: add connecting points to all kind of body diodes

### Removed
- frame

## [1.0.0] - 2020-03-04
### Added
- initial upload for this symbol set
- standard elements: resistors, inductors, capacitors, diodes, transformer, MOSFETs, sources, earth symbols, switches
- standard B6-input-topologies: diode rectifier, thyristor rectifier
- standard B6-output-topologies: IGBT- and MOSFET B6 inverter
- logical operations: AND, NAND, OR, NOR, SUM
- operation amplifier, gain
- signal drawing stuff: square wave, sine wave, triangular wave, xy-diagrams
- evaluation stuff: OK, not OK, flash

[Unreleased]: https://github.com/upb-lea/Inkscape_electric_Symbols/compare/1.3.0...HEAD
[1.3.0]: https://github.com/upb-lea/Inkscape_electric_Symbols/compare/1.2.3...1.3.0
[1.2.3]: https://github.com/upb-lea/Inkscape_electric_Symbols/compare/1.2.2...1.2.3
[1.2.2]: https://github.com/upb-lea/Inkscape_electric_Symbols/compare/1.2.1...1.2.2
[1.2.1]: https://github.com/upb-lea/Inkscape_electric_Symbols/compare/1.2.0...1.2.1
[1.2.0]: https://github.com/upb-lea/Inkscape_electric_Symbols/compare/1.1.0...1.2.0
[1.1.0]: https://github.com/upb-lea/Inkscape_electric_Symbols/compare/1.0.0...1.1.0
[1.0.0]: https://github.com/upb-lea/Inkscape_electric_Symbols/compare/1.0.0...1.0.0
