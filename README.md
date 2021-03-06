**strymonas** is a library providing fast-streams for Scala 3 through the technology of staging and partial evaluation. It has its origins in a [paper](https://dl.acm.org/doi/10.1145/3093333.3009880) published by Oleg Kiselyov ([okmij.org](http://okmij.org/ftp/)), Aggelos Biboudis ([@biboudis](https://github.com/biboudis)), Nick Palladinos ([@palladin](https://github.com/palladin)) and Yannis Smaragdakis [site](https://yanniss.github.io/) and this repo has its aim into making this library available for Scala 3. The initial prototypes (that correspond directly to the paper, were developed for [Scala/LMS](https://github.com/strymonas/staged-streams.scala) and [OCaml/BER MetaOCaml](https://github.com/strymonas/staged-streams.ocaml)) and the initial commit for the Scala 3 port is based on the case study presented for the [paper](https://biboudis.github.io/papers/pcp-gpce18.pdf) published by Nicolas Stucki [@nicolasstucki](https://github.com/nicolasstucki).

[![Build Status](https://travis-ci.org/strymonas/strymonas.svg?branch=master)](https://travis-ci.org/strymonas/strymonas)

## Building strymonas

strymonas is built with SBT 1.3.8 or later and uses the [sbt-dotty](https://github.com/lampepfl/dotty/tree/master/sbt-dotty) plugin for Scala 3.

* Use `sbt run` to run the tests.
* Use `sbt bench/jmh:run` to run the benchmarks

## Contributors

* Oleg Kiselyov ([okmij.org](http://okmij.org/ftp/))
* Aggelos Biboudis ([@biboudis](https://github.com/biboudis))
* Nick Palladinos ([@palladin](https://github.com/palladin))
* Yannis Smaragdakis ([yanniss](https://yanniss.github.io/))
* Nicolas Stucki ([@nicolasstucki](https://github.com/nicolasstucki))
