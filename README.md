# Gemini [![Build Status](https://github.com/anishathalye/gemini/workflows/CI/badge.svg)](https://github.com/thodson-usgs/usgs-latex-poster-template/actions?query=workflow%3ACI)

A USGS-themed fork of the gemini LaTeX [beamerposter] theme.

## Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Arial] font, which is installed on Ubuntu with `sudo apt-get install ttf-mscorefonts-installer`

## Usage

1. Copy the files in this repository (or clone the repository)

1. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Optionally, make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking.

1. Run `make` to build your poster

