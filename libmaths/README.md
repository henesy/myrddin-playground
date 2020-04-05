# Libmaths

Miscellaneous mathematical functions for Myrddin. 

## Build

	mbld

## Test

	mbld test

## Install

	mbld install

## Usage

API reference:

	pkg maths =
		// Computes linear interpolation
		generic lerp	: (a : @f, b : @f, t : @f → @f) :: numeric,floating @f
		
		// Maximum of two values
		generic max		: (a : @t, b : @t → @t) :: numeric @t
	;;

