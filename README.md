# num

[![Build Status](https://travis-ci.org/xyproto/num.svg?branch=master)](https://travis-ci.org/xyproto/num) [![GoDoc](https://godoc.org/github.com/xyproto/num?status.svg)](http://godoc.org/github.com/xyproto/num)

Go module that provides a number type where numbers are stored internally as fractions.

Floating point numbers (`float64`) can be converted to this number type and back.

Includes a small command line utility for converting floats to fractions and for reducing fractions. Can return unicode fractions.

    go get -u github.com/xyproto/num/cmd/dog

Example use:

    dog 2/5
    dog 0.8
    dog 123
