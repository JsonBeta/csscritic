CSS critic
==========

A lightweight framework for regression testing of Cascading Style Sheets.

See example/RegressionRunner.html for an example.

[![Build Status](https://secure.travis-ci.org/cburgmer/csscritic.png?branch=master)](http://travis-ci.org/cburgmer/csscritic)

How it works
------------

CSS critic checks your current layout constantly against a reference image you have provided in the past. If your layout breaks (or changes - regression tests can't tell) your tests fail.

Limitations
-----------

Currently works in Firefox only.
 