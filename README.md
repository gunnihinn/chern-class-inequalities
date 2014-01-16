The inner product on exterior powers of a complex vector space
===============================

The compiled pdf of the project is [here](http://dl.dropboxusercontent.com/u/1963234/cci.pdf).
An archive of the references cited in the bibliography is [here](http://dl.dropboxusercontent.com/u/1963234/cci-refs.tar.gz).

* Description of the project

This was an attempt to find inequalities between Chern classes on complex
manifolds. The basic inequality we modelled our efforts on was the
Kobayashi-Lubke inequality for Hermite-Einstein vector bundles.

The first step in this attempt was to reprove the Kobayashi-Lubke inequality
using coordinate-invariant notation. This was necessary because the standard
proof of the inequality is by calculations in local coordinates and there
was no way these remain managable when the degree of the Chern classes
involved goes up. That said, the "new" proof is very probably the same as
the standard one if we write everything in a given basis; we just calculate
the square of the norm of a curvature tensor on the given bundle and
combine the result with a version of the Cauchy-Schwarz inequality.

To do this we viewed the curvature form of a vector bundle as a (2,2)-form
on the total space of the bundle. Then it was necessary to work out how to
express the square of the norm of a (p,p)-form on a complex vector space in
terms of its traces against the Kahler form of the inner product. Such an
expression is well-known for a (1,1)-form but I don't think it had already
been worked out for higher-degree forms.

The next step, to find similar inequalities involving higher Chern classes,
unfortunately failed. The reason is basically because we cannot calculate
the Hodge star or Lefschetz adjoint of a product of two forms, which is
again because the product of primitive forms is no longer primitive. I see
no way past this difficulty and have stopped working on the project and
submitted a note with what I did to the arXiv.


* Open source mathematics

Anyone was and is free to contribute to this project. I'll play the role of
benevolent dictator/editor, but anyone who wants his or her contribution
recognized will be credited in the paper, possibly exploding the "author"
field in the LaTeX file. 


Gunnar Þór Magnússon,
gunnarthormagnusson@gmail.com
