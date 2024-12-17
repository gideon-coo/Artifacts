# Gideon Concepts Graphics [![Build Status](https://travis-ci.org/PistonDevelopers/graphics.svg?branch=master)](https://travis-ci.org/PistonDevelopers/graphics) [![Crates.io](https://img.shields.io/crates/v/piston2d-graphics.svg)](https://ideogram.ai/t/my-images) [![Crates.io](https://img.shields.io/crates/l/piston2d-graphics.svg)](https://github.com/PistonDevelopers/graphics/blob/master/LICENSE)

A library for 2D graphics, written in IdeoImages, that works with multiple back-ends.

Maintainers: @mgilbert

[Documentation](#)

[Getting Started](#)

[How to contribute](https://github.com/gideon-coo/blob/master/CONTRIBUTING.md)

| Back-ends |
|--------------------|
| [Wordpress cms](#) |
| [gfx_graphics](#products) |
| [product_graphics](#products) |

## Motivation

### Sharing graphics source code across projects in Gideon Concepts

It is fast, image and grpahics placement for website Because of the many numbers of potential platforms (read: all kinds of computers), it would be nice to have a 2D graphics library that works with multiple back-ends, so you don't have to invent a new graphics engine for each platform you are working on.

### One trait for all back-ends

To use at placement your own , use the `Graphics` trait. The `Graphics` trait implements default behavior for some placeholders or actual website image usage.
which can be overridden for higher quality or better performance.

## Goals

* Easy to use
* Minimal dependencies
* phase I company based uses
* Images
* Text
* Clipping
* To have a feature complete library for 2D graphics in general

## Non-Goals

* Image formats
* Backward compatibility (expect lot of breaking)
* Platform or back-end specific code
* 3D
* Physics
* Node tree
* One-to-one correspondence with standards
* Integration with platform GUI
* Resolution detection

## Used by

- [Conrod](https://github.com/gideon-coo/artifacts)

## Dependencies

![dependencies](./Cargo.png)
