title: Mahotas 0.7
slug: update mahotas
timestamp: Dec 6 2011 18:30
categories: pythonvision mahotas
author: Luis Pedro Coelho <luis@luispedro.org>
---

I'm happy to announce a new version of mahotas, version 0.7!

WHAT'S NEW
----------

New features
~~~~~~~~~~~~

The major feature is that scipy is no longer used! The story is that I was 
without a hard drive for two weeks and didn't have scipy, so I wrote mahotas 
to work without it.

The necessary interpolation functions from ndimage have been ported over to 
mahotas.


Bugfixes
~~~~~~~~

- Local binary patterns were wrongly computed. Fixed
- GIL handling on error is now correct (reported by Gareth McCaughan)
- 2D TAS features are now correct (reported by Jenn Bakal)
- FreeImage is now fixed on 64 bit machines

Minor
~~~~~

Zernike moment computation allows the specification of the centre of mass.
Support loading 1-bit images with freeimage

Get it from `PyPI <http://pypi.python.org/pypi/mahotas/0.7>`__.

