.. -*- coding: utf-8 -*-

.. _C++_rst:

=============
Project Name
=============

Defined in header <Project Name>

Overview
========

Class Project Name provides a example to quick start a C++ document.

Public Types
=============

.. list-table::
    :widths: 1 4
    :align: left

    * - enum
      - :cpp:enum:`ExampleEnum {Const1, Const2} <ExampleEnum>`

Properties
===========

.. list-table::
    :widths: 1 4
    :align: left

    * - bool
      - :cpp:member:`example`

Public Functions
=================

.. list-table::
    :widths: 1 4
    :align: left

    * -
      - :cpp:func:`Example() <Example::Example()>`

    * -
      - :cpp:func:`~Example() <Example::~Example()>`

Static Public Functions
========================

.. list-table::
    :widths: 1 4
    :align: left

    * - bool
      - :cpp:func:`staticExample()`

    * - void
      - :cpp:func:`setStaticExample(bool) <setStaticExample()>`

Detailed Description
=====================

Class Project Name provides a example to quick start a C++ document.

Member Type Documentation
==========================

.. cpp:enum:: ExampleEnum

.. list-table::
    :widths: 4 2 4
    :align: left
    :header-rows: 1

    * - Constant
      - Value
      - Description

    * - Example::Const1
      - 0
      - Const value.

    * - Example::Const2
      - 1
      - Const value.

Property Documentation
=======================

.. cpp:member:: bool example

This property holds whether the timer triggers the interval action when interval timeout occurs.

If true, the interval action will be triggered after every interval period unless timeout occurs. The default value is false.

-------------------
Access functions:
-------------------

.. list-table::
    :widths: 1 4
    :align: left

    * - bool
      - :cpp:func:`staticExample() <staticExample()>`

    * - void
      - :cpp:func:`setStaticExample(bool) <setStaticExample()>`


Member Function Documentation
===============================

.. cpp:function:: explicit Example::Example() noexcept

Construct a Example object.

.. cpp:function:: Example::~Example()

Destruct a Example object.

.. cpp:function:: static bool Example::staticExample()

Returns property example.

.. cpp:function:: static void Example::setStaticExample(bool)

Set property example.