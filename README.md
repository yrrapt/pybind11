# pybind11 — Seamless operability between C++11 and Python

This is a fork of the [pybind11](https://github.com/pybind/pybind11.git) project, provided under a BSD-style license.  Please see the github website for documentation and other information.

This fork contains small modifications to how generated Python functions' docstrings are formatted, so that it is easy to generate [stub files](https://mypy.readthedocs.io/en/stable/stubs.html) with typehints that make working in an IDE much easier.  The [pybind11_generics](https://github.com/bluecheetah/pybind11_generics.git) project contains scripts and extra C++ classes that help generate nice stub files.
