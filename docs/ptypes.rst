.. ptypes.rst
.. Copyright (c) 2013-2016 Pablo Acosta-Serafini
.. See LICENSE for details
.. py:module:: pexdoc.ptypes

#############
ptypes module
#############

This module provides several pseudo-type definitions which can be enforced
and/or validated with custom contracts defined using the
:py:mod:`pexdoc.pcontracts` module

************
Pseudo-types
************

.. _FileName:

FileName
--------

String with a valid file name

.. _FileNameExists:

FileNameExists
--------------

String with a file name that exists in the file system

.. _Function:

Function
--------
Callable pointer or :code:`None`

.. _NonNegativeInteger:

NonNegativeInteger
------------------
Integer greater or equal to zero

.. _NonNullString:

NonNullString
-------------
String of length 1 or higher

.. _OffsetRange:

OffsetRange
-----------
Number in the [0, 1] range

.. _PositiveRealNum:

PositiveRealNum
---------------
Integer or float greater than zero or :code:`None`

.. _RealNum:

RealNum
-------
Integer, float or :code:`None`

*********
Contracts
*********

.. autofunction:: pexdoc.ptypes.file_name
.. autofunction:: pexdoc.ptypes.file_name_exists
.. autofunction:: pexdoc.ptypes.function
.. autofunction:: pexdoc.ptypes.non_negative_integer
.. autofunction:: pexdoc.ptypes.non_null_string
.. autofunction:: pexdoc.ptypes.offset_range
.. autofunction:: pexdoc.ptypes.positive_real_num
.. autofunction:: pexdoc.ptypes.real_num
