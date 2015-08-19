hdf5-json
=========

Specification and tools for representing HDF5 in JSON

Documentation: http://hdf5-json.readthedocs.org/en/latest/index.html

h5serv - REST-based service for HDF5 data
===========================================

Introduction
------------
This repository contains a specification, library, and utilities for describing HDF5 content in JSON. 
The utilities can be used to convert any HDF5 file to JSON or from a JSON file (using the convention 
described here to HDF5).

The library is useful for any Python application that needs to translate between HDF5 objects and JSON 
serializations.  In addition to the utilities provided in this repository, the library is used by HDF 
Server (a RESTful web service for HDF5), and HDF Product Designer (an application for creating product 
designs).   

This respository also include utilities to generate code in Fortran or Python based on a JSON file.
See util/codegen/.

Websites
--------

* Main website: http://www.hdfgroup.org
* Source code: https://github.com/HDFGroup/hdf5-json
* Mailing list: hdf-forum@lists.hdfgroup.org <hdf-forum@lists.hdfgroup.org>
* Documentation: http://hdf5-json.readthedocs.org

Related Projects
----------------
* HDF Server: https://www.hdfgroup.org/projects/hdfserver/ 
* Product Designer: https://wiki.earthdata.nasa.gov/display/HPD/HDF+Product+Designer


Installation
-------------

Clone the repository.  hd5tojson and jsontoh5 convertors are in the util directory.
See docs/Installation.rst for step by step instructions.

 
Uninstalling
------------

Just remove the install directory and all contents to uninstall.

    
Reporting bugs (and general feedback)
-------------------------------------

Create new issues at http://github.com/HDFGroup/hdf5-json/issues for any problems you find. 

For general questions/feedback, please use the list (hdf-forum@lists.hdfgroup.org).

