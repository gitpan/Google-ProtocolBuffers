Google-ProtocolBuffers
==
[![Build Status](https://travis-ci.org/csirtgadgets/google-protocolbuffers-perl.png?branch=stable)](https://travis-ci.org/csirtgadgets/google-protocolbuffers-perl)

Google Protocol Buffers is a data serialization format.
It is binary (and hence compact and fast for serialization)
and as extendable as XML; its nearest analogues are Thrift and ASN.1.
There are official mappings for C++, Java and Python languages;
this library is a mapping for Perl.

INSTALLATION

To install this module type the following:
```
   perl Makefile.PL
   make
   make test
   make install
```
DEPENDENCIES

This module requires these other modules and libraries:
```
    Parse::RecDescent
    Math::BigInt
    Class::Accessor
```
COPYRIGHT AND LICENCE

Copyright (C) 2008 by Igor Gariev, <gariev@hotmail.com>
Copyright (C) 2013 by the CSIRT Gadgets Foundation <csirtgadgets.org>

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself, either Perl version 5.10.0 or,
at your option, any later version of Perl 5 you may have available.