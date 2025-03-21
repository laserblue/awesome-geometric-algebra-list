# Geometric Algebra Resources

A curated list of Geometric Algebra resources, inspired by [awesome](https://github.com/sindresorhus/awesome) lists. Also see [pygae/awesome-geometric-algebra](https://github.com/pygae/awesome-geometric-algebra), [Geometric Algebra Explorer](https://ga-explorer.netlify.app/index.php/ga-online-resources/)  and [ Geometric Algebra: A collection of useful resources](https://bleyer.org/dw/doku.php?id=geometric_algebra)

**NOTE** In order to avoid ambiguity and confusion, the term "**Geometric Algebra**" has been appropriated here to refer exclusively to the unified mathematical formalism developed by **David Hestenes** and others for use in Physics, Mathematics and Computer Science. It is not used as merely another term for **Clifford Algebra** since it has been designed to supercede several different mathematical formalisms used in Physics that have redundant content.  

### Introductions

- [Clifford Algebra: A visual introduction](https://slehar.wordpress.com/2014/03/18/clifford-algebra-a-visual-introduction/) (blog post)
- [Imaginary Numbers Are Not Real](http://geometry.mrao.cam.ac.uk/wp-content/uploads/2015/02/ImagNumbersArentReal.pdf) by **Stephen Gull**, **Anthony Lasenby**, and **Chris Doran**
- [Primer on Geometric Algebra for introductory mathematics and physics](https://davidhestenes.net/geocalc/GA_Primer/GA_Primer/)
- [Let's remove Quaternions from every 3D Engine: Intro to Rotors from Geometric Algebra](https://www.youtube.com/watch?v=Idlv83CxP-8) by **Marc ten Bosch** YouTube Channel
- [Oersted Medal Lecture 2002: Reforming the Mathematical Language of Physics](https://davidhestenes.net/geocalc/pdf/OerstedMedalLecture.pdf) by **David Hestenes**
- [A Survey of Geometric Algebra & Geometric Calculus](http://faculty.luther.edu/~macdonal/GA&GC.pdf) by **Alan MacDonald**
- [Geometric Algebra](http://arxiv.org/abs/1205.5935 "Geometric Algebra") by **Eric Chisolm**, good for learning the technical details

### Libraries

#### Javascript
  - [ganja.js](https://github.com/enkimute/ganja.js) :: a GA generator in javascript

#### Python
  - [galgebra](https://github.com/pygae/galgebra) :: symbolic GA package for sympy
  - [kingdon](https://github.com/tBuLi/kingdon) :: A symbolically optimized Geometric Algebra library with PyTorch/NumPy/SymPy/etc. compatibility and ganja.js visualization.
  - [clifford](https://github.com/pygae/clifford) :: a numerical GA package in python
  - [tfga](https://github.com/RobinKa/tfga) :: Tensorflow implementation of GA in python
  - [lean-ga](https://github.com/pygae/lean-ga) :: GA proof verification

#### Julia
  - [SimpleGA: A Lightweight Geometric Algebra Library](https://github.com/MonumoLtd/SimpleGA.jl) :: A simple, fast implementation of Geometric Algebra in Julia
  - [Grassmann.jl](https://github.com/chakravala/Grassmann.jl) :: GA in julia
  - [GeometricAlgebra.jl](https://velexi-research.github.io/GeometricAlgebra.jl/stable/)
    https://github.com/velexi-research/GeometricAlgebra.jl
  - [Multivectors.jl]
  - [Jollywatt/GeometricAlgebra.jl]
  - [serenity4/GeometricAlgebra.jl]
  - [GAlgebra.jl]

  #### C++
  - [Garamon](https://github.com/vincentnozick/garamon) :: C++ generator
  - [gal](https://github.com/jeremyong/gal) :: C++ expression compiler for GA

 ### Software

     - Maple ??? Clifford Algebra packages
     - Mathematica
      [gapauli](https://github.com/peeterjoot/gapauli) A geometric algebra Mathematica module for Euclidean 2D and 3D spaces using the Pauli basis representation as a backend, and a Mathematica module for STA (relativistic space with a +,-,-,- signature).
  
 ### GitHub Repositories

 - [Geometric Algebra Multivectors For Numeric Computing](https://github.com/geometryzen/multivectors)

  ### GeoGebra

  - [Geometric Algebra (Clifford Algebra) Author:JimSmithInChiapas Topic:Algebra, Geometry](https://www.geogebra.org/m/qzDtMW2q)

### Online IDE's, SDK's and Computational Modeling Workspaces and Playgrounds

- [STEMCstudio](https://www.stemcstudio.com/) by George C. Holmes
- [The CoffeeShop](https://enkimute.github.io/ganja.js/examples/coffeeshop.html#pga2d_points_and_lines)
- [Kingdon Teahouse](https://tbuli.github.io/teahouse/lab/index.html) 
- ??? CoCalc using a library such as galgebra and sympy

### Websites and Hypermedia

- [University of Cambridge Geometric Algebra Research Group](https://geometry.mrao.cam.ac.uk/)
- [biVector.net](https://bivector.net/)
- [The CoffeeShop](https://enkimute.github.io/ganja.js/examples/coffeeshop.html#pga2d_points_and_lines)
- [Let's remove Quaternions from every 3D Engine (An Interactive Introduction to Rotors from Geometric Algebra)](https://marctenbosch.com/quaternions/) by **Marc ten Bosch**
- [Geometric Algebra Explorer](https://ga-explorer.netlify.app/index.php/ga-online-resources/)
- [Geometric Algebra Tutorial](https://geometricalgebratutorial.com/)
- [Papers in Geometric Algebra and Foundations of Physics](https://www.faculty.luther.edu/~macdonal/index.html#geometric-algebra) **Alan Macdonald**
- [Geometric Algebra - Wikipedia](https://en.wikipedia.org/wiki/Geometric_algebra)
 
- [Geometric Algebra — a guided tour / Yao Liu](https://observablehq.com/@liuyao12/geometric-algebra) may not be conforming to the Hestenes formalism but uses ganga.js
- [Geometric Algebra in Three Dimensions](https://www.cv.nrao.edu/~mmorgan2/resources/geo3.html) a slightly rogue website as failure to adopt the unified formalism developed by Dr. David Hestenes, use of the term "Clifford Product" and  a statement made regarding early introduction of Geometric Algebra to University undergraduates and high school students suggests an ignorance of the work of David Hestenes and others specifically on this matter over the last 30 - 40 years. It has been like watching tar drop. First David Hestenes wrote many times about the difficulty of getting his peers and graduate students to adopt the formalism and then undergraduates and high schools. All the while there has been the same kind of establishment resistance to reform in high school and university as in education reform in general with people wanting to keep knowledge silos and established curriculums in place. 
  
 "While I agree with this ambition in general, I believe its advocates make the mistake of jumping too quickly into highly specialized disciplines such as quantum physics and general relativity. While it is good to know that each of these important subjects can be covered by the geometric algebra toolset, true adoption as the standard language for mathematical physics must start at a much more basic level. Preferably, in my view, it should be introduced to students as soon as they are prepared to advance beyond purely scalar mathematics and begin to talk about higher-dimensional objects like vectors."

 "...true adoption as the standard language for mathematical physics must start at a much more basic level."
  
### Videos

- [Geometric Algebra Series](https://www.youtube.com/playlist?list=PLpzmRsG7u_gqaTo_vEseQ7U8KFvtiJY4K) by **Mathoma**
- [Geometric Algebra for Computer Graphics - Siggraph 2019](https://www.youtube.com/watch?v=tX4H_ctggYo) by **Charles Gunn**
- [Geometric Algebra and Calculus Videos](https://www.youtube.com/channel/UCymE67THrWoeTABxzJm1wdg/videos) by **Alan Macdonald**
- [From Vectors to Multivectors](https://www.youtube.com/playlist?list=PLQ6JJNfj9jD_H3kUopCXkvvGoZqzYOzsV) by **Nick Okamoto**, a 3-part intro on Youtube
- [Self-Study Geometric Algebra!](https://youtu.be/Egb-qlb8870?si=h4mh687f0XUE8lrM) by the **Eccentric** YouTube Channel
- [GAME2020 3. Professor Anthony Lasenby. A new language for physics.](https://youtu.be/m7v2IUJtC3g?si=Dp0BVK_lt8VCab29) on the **Bivector** YouTube Channel
- [Amazing Things You Can Do in Geometric Algebra - Explained](https://youtu.be/xGuN6KM_D18?si=v6pO-aJ066zdb5pk) on the **ThoughtThrill** YouTube Channel
- [Good geometric algebra textbooks (Clifford algebras)](https://youtube.com/shorts/-KUIR99nF6k?si=H3mOSBaxtLUwxiL2) on the **UV Wizard** YouTube Channel
- [Geometric Algebra, First Course, Episode 00: High Level Overview](https://www.youtube.com/watch?v=e5D7Bma9Vhw) by **David Geo Holmes** (STEMCstudio) YouTube Channel
- [SimpleGA: A Lightweight Geometric Algebra Library](https://www.youtube.com/watch?v=zq3wHwWf4WA) by **Chris Doran**, JuliaCon 2023, The Julia Programming Language
- [David Hestenes - Tutorial on Geometric Calculus](https://youtu.be/ItGlUbFBFfc?si=5exp8FaM1iaEiOHA) on the **Nomen Nominandum** YouTube Channel
- [Quaternions in Geometric Algebra and Physics (HestenesJMM2019)](https://www.youtube.com/watch?v=zsQQ7djCg_Y) a presentation by **David Hestenes** (Department of Physics, Arizona State University), Joint Mathematics Meetings 2019 (JMM2019) AMS Special Session on Quaternions II Baltimore, Wednesday January 16, 2019. on the **Quaternion Notices** YouTube Channel
- [Solution Strategies for Geometric (Clifford) Algebra Problems](https://youtu.be/HfX8zh8vKro?si=LJ_7GcoTz_qaRJ4h) on the **Pre-University Geometry** YouTube Channel
- [GA for Introductory Physics](https://youtu.be/Eauj0JJEyJ8?si=deOlU-GCRPcawcbQ) on the **Katelyn Spadavecchia** YouTube Channel
- [Projective Geometric Algebra for Paraxial Geometric Optics](https://www.youtube.com/watch?v=X_k7dNitHM0) on the **Katelyn Spadavecchia** YouTube Channel
- [The power of Geometric Algebra Computing for Mathematica](https://www.youtube.com/watch?v=1cWGV2qaBHo) on the **Wolfram** YouTube Channel

  
  
  #### YouTube Channels
  [Bivector](https://www.youtube.com/@bivector)
  
  [sudgylacmoe](https://www.youtube.com/@sudgylacmoe)
  
  [EccentricTuber](https://www.youtube.com/@EccentricTuber)
  
  [PeeterJoot](https://www.youtube.com/@PeeterJoot)

  [Pre-University Geometric Algebra Videos](https://www.youtube.com/@pre-universitygeometricalg5862)
  
  [JimSmithInChiapas](https://www.youtube.com/@JimSmithInChiapas)
  

  #### YouTube Playlists
   - [Geometric Algebra for High Schoolers](https://www.youtube.com/playlist?list=PL4P20REbUHvzPW8rkHVyu9l20fJ5Iih2M) by **JimSmithInChiapas**
   - [Geometric Algebra](https://www.youtube.com/playlist?list=PLLvlxwbzkr7igd6bL7959WWE7XInCCevt) by **Alan Macdonald**
   - [Geometric Calculus](https://www.youtube.com/playlist?list=PLLvlxwbzkr7i6DlChcYEL7nJ8R9ZuV8JA) by **Alan Macdonald**
   - [Geometric Algebra for Physicists](https://www.youtube.com/playlist?list=PL4TOpi2EWY8a7dmFb7DbfPNKEAIZWi_rr) by the **Eccentric** YouTube Channel
  
  

### Books

- [Geometric Algebra for Physicists](http://geometry.mrao.cam.ac.uk/2007/01/geometric-algebra-for-physicists/) by **Chris Doran** and **Anthony Lasenby**
- [Linear and Geometric Algebra](http://faculty.luther.edu/~macdonal/laga/index.html) and [Vector and Geometric Calculus](http://faculty.luther.edu/~macdonal/vagc/index.html) by **Alan Macdonald**
- [Geometric Algebra For Computer Science, An Object Oriented Approach to Geometry](http://www.geometricalgebra.net/) by **Leo Dorst, Daniel Fontijne and Stephen Mann**
- [Geometric Algebra with Applications in Engineering](http://link.springer.com/book/10.1007/978-3-540-89068-3) by **Christian Perwass**
- [Foundations of Geometric Algebra Computing](http://link.springer.com/book/10.1007/978-3-642-31794-1) by **Dietmar Hildenbrand**
- [Space-Time Algebra](http://www.springer.com/us/book/9783319184128) by **David Hestenes**
- [New Foundations for Classical Mechanics](https://link.springer.com/book/10.1007/0-306-47122-1) (1999), 2nd Ed. by **David Hestenes**
- [Geometric Algebra for Electrical Engineers](https://peeterjoot.com/writing/geometric-algebra-for-electrical-engineers/) by **Peeter Joot**

- [Clifford Algebra to Geometric Calculus](https://math.mit.edu/~dunkel/Teach/18.S996_2022S/books/Hestenes-Sobczyk1984_Book_CliffordAlgebraToGeometricCalc.pdf)

### Papers
#### Geometric Algebra
  - [Papers in Geometric Algebra and Foundations of Physics](https://www.faculty.luther.edu/~macdonal/index.html#geometric-algebra) **Alan Macdonald**


#### Geometric Calculus

- [Geometric Calculus R & D Website](https://davidhestenes.net/geocalc/) in the **David Hestenes** Archive.
- [Tutorial on Geometric Calculus](https://davidhestenes.net/geocalc/pdf/Tutorial%20on%20Geometric%20Calculus.pdf)
- [Peeter Joot's Blog](https://peeterjoot.com/tag/geometric-calculus/)
- 

### Disciplines
#### Physics

- [Special Relativity with Geometric Algebra - Introduction](https://geometricalgebratutorial.com/sr-intro)
  
#### Computer Science

  - [Haskell - All Hail Geometric Algebra!](https://crypto.stanford.edu/~blynn/haskell/ga.html)
  - [Geometric algebra:
a computational framework
for geometrical applications
(Part I: algebra)](https://cs.uwaterloo.ca/~smann/Papers/dorst-mann-I.pdf) by **Leo Dorst** and **Stephen Mann**
  -[From Grassmann’s vision to Geometric Algebra Computing](http://www.gaalop.de/dhilden_data/GrassmannComputers.pdf) by **Dietmar Hildenbrand**
  - [Compiling Geometric Algebra Computations into Reconfigurable Hardware Accelerators](https://www.esa.informatik.tu-darmstadt.de/assets/publications/materials/2010/2010_Dagstuhl.pdf) by **Jens Huthmann**,**Peter Müller**,**Florian Stock**,**Dietmar Hildenbrand** and **Andreas Koch**

### Historical

- [The Genesis of Geometric Algebra: A Personal Retrospective](https://davidhestenes.net/misc/Hestenes_2016_-_The_Genesis_of_Geometric_Algebra,_A_Personal_Retrospective.pdf) by **David Hestenes**
- [The Vector Algebra War](https://youtu.be/_AaOFCl2ihc?si=w-dp0KaZ9OU5a7SF)


- [Applied Geometric Algebra (1976)](https://ocw.mit.edu/courses/res-8-001-applied-geometric-algebra-spring-2009/95490d4f704fabc782963546923670e1_MITRES_8_001_lec_complete.pdf) by **Laszlo Tisza**
  [Applied Geometric Algebra, MIT OpenCourseWare](https://ocw.mit.edu/courses/res-8-001-applied-geometric-algebra-spring-2009/)
  
  Uses **Geometric Algebra** as a synonym for **Clifford Algebra** and does not use the unified notation developed by **David Hestenes** et al.
 

### Biographical

  - [An Interview with David Hestenes: His life and achievements](https://davidhestenes.net/misc/Hestenes_2012_-_Interview_(Tasar).pdf) by **Mehmet Fatih Taşar**, **Sedef Canbazoğlu Bilici**, **Pınar Fettahlıoğlu**
Gazi Üniversitesi, TURKEY, Received 22 April 2012; accepted 29 April 2012
