# Awesome Side-Channel Attacks

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources for side-channel attacks research and implementation.

## Contents

- [Resources](#resources)
  - [Introduction](#introduction)
  - [Tutorials](#tutorials)
  - [Leakage Assessment](#leakage-assessment)
  - [Database](#database)
  - [Conference](#conference)
- [Software](#software)
- [Hardware](#hardware)

---

# Resources

## Introduction

* [What Is a Side Channel Attack?](https://www.wired.com/story/what-is-side-channel-attack/)
* [Power Side-Channel Attack Analysis: A Review of 20 Years of Study for the Layman](https://www.mdpi.com/2410-387X/4/2/15)
* [Introduction to differential power analysis](https://link.springer.com/article/10.1007/s13389-011-0006-y)

## Tutorials

* [Chipwhisperer wiki](https://chipwhisperer.readthedocs.io/en/latest/)
* [SCAAML AES side-channel attacks tutorial](https://github.com/google/scaaml/tree/master/scaaml_intro)

## Leakage Assessment

* [Hypothesis testing for leakage assessment in side-channel analysis](https://cescalab.cs.ru.nl/hypothesis-testing-for-leakage-assessment-in-side-channel-analysis/)
* [A testing methodology for side-channel resistance validation](https://csrc.nist.gov/csrc/media/events/non-invasive-attack-testing-workshop/documents/08_goodwill.pdf)
* [Leakage Assessment Methodology](https://www.iacr.org/archive/ches2015/92930478/92930478.pdf)
* [Leakage Detection with the x2-Test](https://tches.iacr.org/index.php/TCHES/article/view/838)
* [Confident leakage assessment — A side-channel evaluation framework based on confidence intervals](https://ieeexplore.ieee.org/abstract/document/8342178)
* [Fast Leakage Assessment](https://eprint.iacr.org/2017/624.pdf)

## Database

* [ASCAD](https://github.com/ANSSI-FR/ASCAD) - Databases that aim at providing a benchmarking reference for the SCA community
* [XS-Leaks](https://github.com/xsleaks/xsleaks) - A collection of browser-based side-channel attack vectors

## Conference

* [COSADE: Constructive Side-Channel Analysis and Secure Design](https://www.cosade.org/)
* [CHES: Cryptographic Hardware and Embedded Systems](https://ches.iacr.org/)

# Software

* [SCALib](https://github.com/simple-crypto/SCALib) - A Python library that contains state-of-the-art tools for side-channel security evaluation
* [ChipWhisperer](https://github.com/newaetech/chipwhisperer) - An easy to use framework that implements a complete pipeline for power analysis attacks
* [ChipSHOUTER](https://github.com/newaetech/ChipSHOUTER) - The Electromagnetic Fault Injection (EMFI) Platform
* [Lascar](https://github.com/Ledger-Donjon/lascar) - Ledger's Advanced Side-Channel Analysis Repository
* [Daredevil](https://github.com/SideChannelMarvels/Daredevil) - A tool to perform (higher-order) correlation power analysis attacks (CPA)
* [Jlsca](https://github.com/Keysight/Jlsca) - Side-channel toolkit in Julia [[Tutorial](https://github.com/ikizhvatov/jlsca-tutorials)]
* [Pysca](https://github.com/ikizhvatov/pysca) - Toolbox for advanced differential power analysis of symmetric key cryptographic algorithm implementations
* [Pyecsca](https://github.com/J08nY/pyecsca) - Python Elliptic Curve Side-Channel Analysis toolkit
* [Scared](https://gitlab.com/eshard/scared) - A side-channel analysis framework
* [Rainbow](https://github.com/Ledger-Donjon/rainbow) - Generic side-channel and fault injection simulator that makes Unicorn traces
* [Screaming_channels](https://github.com/eurecom-s3/screaming_channels) - Radio side-channels in mixed-signal chips
* [SCA toolbox](https://github.com/AISyLab/side-channel-analysis-toolbox) - Allows known side-channel attacks to be run
* [SCAAML](https://github.com/google/scaaml) - A deep learning framework dedicated to side-channel attacks
* [PROLEAD](https://github.com/ChairImpSec/PROLEAD) - A probing-based leakage detection tool for hardware and software

# Hardware

* [ChipWhisperer](https://chipwhisperer.readthedocs.io/en/latest/) - A complete open-source toolchain for side-channel power analysis and glitching attacks
* [SakuraG](http://www.troche.com/sakura/sakura.html) - Various experimental hardware platforms developed to contribute to research on physical security analysis of cryptographic modules
* [FOBOS](https://cryptography.gmu.edu/documentation/fobos3/index.html) - An "acquisition to analysis" solution which includes all necessary software to control the device under test


