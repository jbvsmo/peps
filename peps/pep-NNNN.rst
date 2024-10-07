PEP: TBD
Title: Range Expressions in Python
Author: João Bernardo Oliveira <jbvsmo@gmail.com>
Sponsor: TBD
Discussions-To: https://discuss.python.org/t/25026
Status: Draft
Type: Standards Track
Created: 06-Oct-2024
Python-Version: 3.14
Post-History: `20-Mar-2023 <https://discuss.python.org/t/25026>`__,
Replaces: 204


Abstract
========

This PEP proposes adding range expressions to Python’s syntax, allowing flexible and optimized sequence generation via expressions between range markers.

Motivation
==========

Currently, range literals are limited to static start, stop, and step values. This proposal enables dynamic expressions, improving code flexibility and readability.

Rationale
=========

This feature enhances Python’s expressiveness, reduces verbosity in iteration patterns, and can be optimized with the upcoming JIT compiler that is currently experimental.

Specification
=============

The proposed syntax introduces range expressions, allowing arbitrary expressions within range markers (e.g., `[start : stop : step]`), compiled into iterable sequences.

Backward Compatibility
=======================

This feature is backward-compatible, as it introduces a new optional syntax without affecting existing code.

Security Implications
=====================

This change has no security implications.

How to Teach This
=================

[How to teach users, new and experienced, how to apply the PEP to their work.]


Reference Implementation
=========================

A proof of concept has been developed and discussed on the Python forums.

Rejected Ideas
==============

[Why certain ideas that were brought while discussing this PEP were not ultimately pursued.]


Open Issues
===========

[Any points that are still being decided/discussed.]


Footnotes
=========

[A collection of footnotes cited in the PEP, and a place to list non-inline hyperlink targets.]


Copyright
=========

This document is placed in the public domain or under the
CC0-1.0-Universal license, whichever is more permissive.
