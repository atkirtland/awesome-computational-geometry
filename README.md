# Awesome Computational Geometry
[![Build Status](https://api.travis-ci.org/atkirtland/awesome-computational-geometry.svg?branch=master)](https://travis-ci.org/atkirtland/awesome-computational-geometry)

A curated list of awesome computational geometry visualizations, frameworks, and resources.

Inspired by [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome Computational Geometry](#awesome-computational-geometry)
  - [Visualizations](#visualizations)
  - [Books](#books)
  - [Papers](#papers)
  - [Frameworks](#frameworks)
  - [Algorithms](#algorithms)
  - [Conferences](#conferences)
  - [Competitive Programming](#competitive-programming)
  - [Open Courses](#open-courses)
  - [University Courses](#university-courses)

## Visualizations

*Applets for Learning*

* [Graham Scan](http://www.algomation.com/player?algorithm=59b4289a338f13040013e41b)
* [Convex Hull](https://visualgo.net/en/convexhull?slide=1)
* [Merge Hull](http://www.algomation.com/player?algorithm=5616c4161ed5fe0300c271f6)
* [Quick Hull](http://www.algomation.com/algorithm/quick-hull-convex-hull)
* [Chan's Algorithm](http://sophiedasinger.github.io/Classwork/163proj/#viz)
* [Kirkpatrick's Point location](http://rkaneriya.github.io/point-location/) - An interactive implementation of Kirkpatrick's point location algorithm. [src](https://github.com/rkaneriya/point-location)
* [Voronoi Diagrams](http://alexbeutel.com/webgl/voronoi.html)
* [Fortune's Algorithm](https://www.desmos.com/calculator/ejatebvup4)
* [Point/Line Duality](http://students.cec.wustl.edu/~tdeck/duality/)
* [kd-tree](https://opendsa-server.cs.vt.edu/ODSA/AV/Development/kd-treeAV.html?selfLoggingEnabled=false&localMode=false&module=KDtree&JXOP-debug=true&JOP-lang=en&JXOP-code=java&scoringServerEnabled=false&threshold=1.0&points=0&required=False)
* [Configuration Space](https://www.youtube.com/watch?v=SBFwgR4K1Gk)

## Books

* [Computational Geometry: Algorithms and Applications](https://www.amazon.com/Computational-Geometry-Applications-Mark-Berg/dp/3540779736) - Mark de Berg,‎ Otfried Cheong,‎ Marc van Kreveld‎, Mark Overmars: introduction to computational geometry focuses on algorithms. Motivation is provided from the application areas as all techniques are related to particular applications in robotics, graphics, CAD/CAM, and geographic information systems
* [Computational Geometry in C ](https://www.amazon.com/Computational-Geometry-Cambridge-Theoretical-Paperback/dp/0521649765) - a popular introduction to the design and implementation of geometry algorithms arising in areas such as computer graphics, robotics, and engineering design
* [Computational Geometry: An Introduction](https://www.amazon.com/Computational-Geometry-Introduction-Monographs-Computer/dp/0387961313) - by Franco P. Preparata,‎ Michael I. Shamos: This book offers a coherent treatment, at the graduate textbook level, of the field that has come to be known in the last decade or so as computational geometry
* [Algorithms in Combinatorial Geometry](https://www.amazon.com/Algorithms-Combinatorial-Geometry-Monographs-Theoretical/dp/B000QUU1B2) - Herbert Edelsbrunner (1987): a rather advanced exposition of problems and approaches in computational geometry focused on the role of hyperplane arrangements
* [Algorithmic Geometry](https://www.amazon.com/Algorithmic-Geometry-Jean-Daniel-Boissonnat/dp/0521565294) - by Jean-Daniel Boissonnat (Author),‎ Mariette Yvinec (Author),‎ Herve Bronniman (Translator), 1998: a coherent and systematic treatment of the foundations and gives simple, practical algorithmic solutions to problems
* [Discrete and Computational Geometry](https://www.amazon.com/Discrete-Computational-Geometry-Satyan-Devadoss/dp/0691145539) - by Satyan L. Devadoss, Joseph O'Rourke, 2011: offers a comprehensive yet accessible introduction to the intermingling of discrete geometry, a relatively new development in pure mathematics, and computational geometry, an emerging area in applications-driven computer science
* [Interactive Computational Geometry - A taxonomic approach](http://www.clearviewtraining.com/interactive-computational.html) - Jim Arlow, 2014: an interactive introduction to some of the fundamental algorithms of computational geometry with Mathematica

## Notes

*concise accumulations of concepts*

* [David Mount's Lecture Notes](http://www.cs.umd.edu/~mount/754/Lects/754lects.pdf) - CMSC 754 Computational Geometry at the University of Maryland
* [Handbook of Discrete and Computational Geometry](https://www.csun.edu/~ctoth/Handbook/HDCG3.html) - Jacob E. Goodman, Joseph O'Rourke, and Csaba D. Tóth: the definitive reference work
* [Handbook of Computational Geometry](https://www.amazon.com/Handbook-Computational-Geometry-J-Sack-ebook/dp/B00QM3S1SC) - by J. R. Sack (Editor),‎ J. Urrutia (Editor), 1998: an overview of key concepts and results in Computational Geometry
* [Computing in Euclidean Geometry](https://www.amazon.com/Computing-Euclidean-Geometry-Lecture-Notes/dp/9810218761) - by Ding-Zhu Du (Editor),‎ Frank Hwang (Editor); 1995: a collection of surveys and exploratory articles about recent developments in the field of computational Euclidean geometry

## Papers

* [Triangulating a Simple Polygon in Linear Time](https://www.cs.princeton.edu/~chazelle/pubs/polygon-triang.pdf)

## Frameworks

*frameworks, libraries*

* [CGAL](https://www.cgal.org/) - A software project that provides easy access to efficient and reliable geometric algorithms in the form of a C++ library
* [Wykobi](http://www.wykobi.com/index.html) - Wykobi is an extremly efficient, robust and simple to use C++ 2D/3D oriented computational geometry library.
* [geometry3Sharp](https://github.com/gradientspace/geometry3Sharp) - Open-Source (Boost-license) C# library for geometric computing.
* [Computational Geometry Software Libraries](http://jeffe.cs.illinois.edu/compgeom/software.html) - Jeff Erickson @ UIUC large collections and libraries of geometric software
* [The Stony Brook Algorithm Repository](http://www3.cs.stonybrook.edu/~algorith/major_section/1.6.shtml) - based on [The Algorithm Design Manual](https://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693)
* [Geometric Tools](https://www.geometrictools.com/index.html) - a library of source code for computing in the fields of mathematics, graphics, image analysis and physics (includes some computational geometry algorithms)
* [GeoLib](http://www.geolib.co.uk/) - 2005: a fast, efficient, computational geometry library available in C++, C# and Java

## Algorithms

*frameworks that attempt to solve a particular problem rather than a general set*

* [hull.js](https://github.com/AndriiHeonia/hull) - JavaScript library that builds concave hull by set of points
* [S2 Geometry Library](https://github.com/google/s2geometry) - a package for manipulating geometric shapes. Unlike many geometry libraries, S2 is primarily designed to work with spherical geometry, i.e., shapes drawn on a sphere rather than on a planar 2D map. This makes it especially suitable for working with geographic data.

## Conferences

### Strictly Computational Geometry

* [Symposium on Computational Geometry](http://www.computational-geometry.org/) - annual SoCG
* [The Canadian Conference on Computational Geometry](http://www.cccg.ca/) - an annual international event for the dissemination of new results in the fields of computational and combinatorial geometry. The conference is usually held in a Canadian city sometime in mid-August.
* [Japan Conference on Discrete and Computational Geometry, Graphs, and Games](http://www.alg.cei.uec.ac.jp/itohiro/JCDCGG/) - held annually since 1997, except for 2008

### Broader

* [Symposium on Discrete Algorithms](https://www.siam.org/meetings/da18/) - ACM-SIAM, held annually
* [Annual ACM Symposium on Theory of Computing](http://acm-stoc.org/) - STOC covers all areas of research within Algorithms and Computation Theory
* [IEEE Symposium on Foundations of Computer Science](http://ieee-focs.org/) - the flagship conference sponsored by the IEEE Computer Society Technical Committee on the Mathematical Foundations of Computing (TCMF) and covers a broad range of theoretical computer science
* [Annual Allerton Conference on Communications, Control and Computing](http://allerton.csl.illinois.edu/) - draws some of the brightest minds from industry, academia and government to discuss innovation in the fields of communication, control and computing

## Competitive Programming

* [HackerEarth](https://www.hackerearth.com/practice/notes/computational-geometry-i-1/) - Ayush Jaggi and Arjit Srivastava
* [TopCoder](https://www.topcoder.com/community/data-science/data-science-tutorials/geometry-concepts-basic-concepts/) - lbackstrom
* [HackerRank](https://www.hackerrank.com/domains/mathematics/geometry)

# Open Courses

*Coursera, OCW, etc.*

* [MIT](https://ocw.mit.edu/courses/mechanical-engineering/2-158j-computational-geometry-spring-2003/) - Prof. Nicholas Patrikalakis, Prof. Takashi Maekawa; 2013

# University Courses

* [Brown University](http://cs.brown.edu/courses/cs252/) - Roberto Tamassia
* [John Hopkins](https://ep.jhu.edu/programs-and-courses/605.727-computational-geometry) - Boon
  * [old](http://www.cs.jhu.edu/~goodrich/teach/geom/) - Goodrich: contains resources
* [Washington University in St. Louis](http://www.cs.wustl.edu/~taoju/cse546/) - Tao Ju

## Contribute

Contributions are welcome! See the [contribution guidelines](CONTRIBUTING.md).

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.
