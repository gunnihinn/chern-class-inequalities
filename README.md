Higher Chern class inequalities
===============================

The compiled pdf of the project is [here](http://dl.dropboxusercontent.com/u/1963234/cci.pdf).
An archive of the references cited in the bibliography is [here](http://dl.dropboxusercontent.com/u/1963234/cci-refs.tar.gz).

* Description of the project and progress so far

This is an attempt to find inequalities between Chern classes on complex
manifolds. The basic inequality we model our efforts on is the
Kobayashi-Lubke inequality for Hermite-Einstein vector bundles.

The first step in this attempt is to reprove the Kobayashi-Lubke inequality
using coordinate-invariant notation. This is necessary because the standard
proof of the inequality is by calculations in local coordinates and there
is no way these remain managable when the degree of the Chern classes
involved goes up. That said, the "new" proof is very probably the same as
the standard one if we write everything in a given basis; we just calculate
the square of the norm of a curvature tensor on the given bundle and
combine the result with a version of the Cauchy-Schwarz inequality.

To do this we view the curvature form of a vector bundle as a (2,2)-form on
the total space of the bundle. Then it is necessary to work out how to
express the square of the norm of a (p,p)-form on a complex vector space in
terms of its traces against the Kahler form of the inner product. Such an
expression is well-known for a (1,1)-form but I don't think it had already
been worked out for higher-degree forms.

The next step, and where the project is now, is to try to find similar
inequalities involving higher Chern classes. The calculations here are
intimidating and we may need to specialize to the case of Kahler-Einstein
manifolds to get anything useful. Right now it's also not clear exactly
what we should try to calculate to obtain the inequalities we hope for.
Have a look if you think you can help!


* Open source mathematics

Anyone is free to contribute to this project. I'll play the role of
benevolent dictator/editor, but if this work abuts to anything noteworthy
then everyone who contributed will be credited in the final result and
involved in publishing it to the world, possibly exploding the "author"
field in the LaTeX file. 


Gunnar Þór Magnússon,
gunnarthormagnusson@gmail.com
