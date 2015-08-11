# Generate simple encapinfo files for applications

## Introduction

`mkencapinfo` is a shell script to generate an `encapinfo` file for
the [`epkg` package manager](https://github.com/perusio/epkg/).  A
very conveninent way to manage applications as packages, particularly
useful for **microservice** based applications.

## Usage

    mkencpainfo -e <email address> <short description of program>

where:

 * `<email address>`: email adress of the maintainer for the package
    being installed.
 
 * `<short description of the the program>`: string describing the
   aplication/package being installed.

Example:

    mkencapinfo -e quux@foobar.com "This is an example description."

## Installation

 1. Clone the repository:

        git clone https://github.com/perusio/mkencapinfo.git

 2. Make the script available in your path using an alias or other
    form of binary installation.

 3. Done.
