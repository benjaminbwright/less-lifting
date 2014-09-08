less-lifting
============

A simple lightweight LESS framework.


Why?
====

This LESS framework is intended to be a simpler collection of LESS tools to speed up front-end development. The aim is to keep the code as simple as possible while taking advantage of the power of CSS pre-processing.


Tools
===============

# Color Palette Mixins

## Introduction

Color palette mixins may be used to auto-generate entire palettes for your web project based upon a base color. Palettes include:

- Shades Palette
- Analagous Palette
- Complementary Palette
- Split Complementary Palette
- Clash Palette
- Triadic Palette
- Tetradic Palette
- Five Tone Palette
- Six Tone Palette

**Shades Palette**

_Usage:_

body {
	.shades-palette(@base-color);
}
