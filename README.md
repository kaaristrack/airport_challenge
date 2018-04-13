# Airport Challenge

[![Build Status](https://travis-ci.org/kaaristrack/airport_challenge.svg?branch=master)](https://travis-ci.org/kaaristrack/airport_challenge)

## Synopsis

Welcome to my repo for the Makers Academy weekend challenge 1:1!

My task was to create an emulation of an airport environment, in which planes can take off and land. To do this, I needed to implement guard classes to defend against the appropriate edge case, e.g planes are only able to take off from their current airport, etc.

### Key Focus

Object-Oriented Design (OOD) & Test-Driven Development (TDD).

## Implementation

1) Clone this repository, and change into the correct directory.
```
$ git https://github.com/kaaristrack/airport_challenge
$ cd airport_challenge
```
2) Open in IRB or PRY.
```
$ pry
  > require './file_collective.rb'
```
3) Create a new airport.
```
$ pry
  > airport = Airport.new
```
4) Populate your new airport with a plane object.
```
> plane = Plane.new
> airport.landing(plane)
=> #<Airport:0x00007ffc10079a18 @airport_hangar=[], @capacity=5, @taxied_planes=0, @weather=#<Weather:0x00007ffc100799c8>>
```
5) Marvel at the automatically updating capacity!

### Demo Reel :movie_camera:

[COMING SOON]
