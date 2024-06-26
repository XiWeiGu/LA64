# Change Log

All notable changes to the "la64" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

- Initial release

## [V0.0.1]
- Highlighting and prompts for supporting scalar registers, basic integer instructions, and basic floating-point instructions

## [V0.0.2]
- Set floating-point instruction color similar to general instructions
- Add highlighting and prompts for register aliases
- Add floating point condition flag register
- Add LASX/LSX registers and instructions
- Add Loongson asm Macros v0.0.1

## [V0.0.3]
- Fixed some ins that cannot be highlighted
- Highlighting comments

## [V0.0.4]
- Avoid using red-colored highlighting for floating-point ins

## [V0.0.5]
- Fixed {xv/v}shuf4i.{b/h/w/d} snippet

## [V0.0.6]
- Fixed highlighting of ffint, bceqz and bcnez

## [V0.0.7]
- Fixed highlighting of {xv/v}haddw and {xv/v}hsubw

## [V0.0.8]
- Fixed highlighting of {ld/ldx}.{hu/bu/wu}

## [V0.0.9]
- Fixed highlighting of {xv/v}{max/min} li.d and la.{local/global}