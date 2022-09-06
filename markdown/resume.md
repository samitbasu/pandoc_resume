Samit Basu, PhD
===============

----

> Inspire and Lead Multidisciplinary Engineering Teams to Innovate, Deliver, 
> and Demystify Technology

----

Experience
---------

**Chief Digital Officer, Smiths Group** (2017-)

Lead digital transformation for Smiths Group through the [Smiths Digital Forge](forge.smiths.com) – a center of technical excellence for the development of software, algorithms and technology to support current and future Smiths’ products and services.  In its first four years, the Forge has delivered software technology for smart infusion pumps, minimum viable product demonstrators for condition monitoring of seals in the oil and gas space, a cyber-secure IoT gateway for hazardous locations, and networked sensor solutions for commercial and residential ducting.  The Forge has also hosted group-wide activities such as a first ever company-wide conference on artificial intelligence, and a self-driving car competition.

- Architected, staffed and lead the Smiths Digital Forge from CEO conception thru construction and operation
- Lead the strategy for the Digital Forge, and supported the digital strategies of John Crane and FlexTek.
- Designed the electronics, gate-ware, and the firmware for a fielded Minimum Viable Product (MVP) dry gas seal
monitoring system
- Invented, prototyped, patented and deployed a time series database for very high throughput telemetry that 
features a simple REST API, ease of integration with Grafana for charting, and a rich set of apps.  The
database is written in Rust.
- Provided leadership, motivation, and engagement for the ~24 talented individuals (scientists, software 
engineers, mechanical and electrical engineers, program management and IT support) that made up the Forge.
- The Smiths Digital Forge had some of the highest employee engagement and satisfaction results from the
internal company survey.

**Chief Technology Officer, Morpho Detection** (2014-2017)

Drive the renewal of core product lines and position technologies for the future.  Shape the technology plan and vision for the company.  Build and staff an internal Research and Technology organization to develop early phase technologies for future products.  Promote a culture of innovation within the organization.  Architect the next generation line of Computed Tomography systems to achieve higher performance, scalable cost, and ease of manufacturing and serviceability.

- Architected and lead the development of a prototype for an open-bearing CT system.
- Invented a new detector concept based on off-the-shelf photo-diodes instead of silicon photo-diode arrays.
- Lead the Research and Technology group - a set of 6 highly talented individuals that covered all aspects of next generation technology development across CT and trace detection.
- Developed a sophisticated software package `Illumina` for fast (>10^8 photons/sec) simulation of CT systems using 
accurate modelling of photon absorption and scattering on a single GPU.

2007-2014: **Chief Engineer, GE Homeland Protection & Morpho Detection**

Invented new, robust radioisotope identification algorithms for handheld personal radiation spectrometers.  Guided research and development efforts at the GE Global Research center.  Lead system design and development for the CTX 5800, a compact explosives detection system deployed globally.  Designed the common software architecture for the CTX product line and oversaw its development and incorporation into the CTX 5800, CTX 9800, and the CTX 9400.  


2000-2007: **Electrical Engineer, GE Global Research Center**

Lead system design efforts for next generation medical CT systems.  Lead system analysis and design efforts for flat-panel based preclinical CT systems.  Collaborated with luminaries within GE and academia to develop new CT reconstruction algorithms. Manage projects funded by GE Healthcare for research and development in advanced reconstruction algorithm development.  Researched and developed new advanced CT reconstruction algorithms and their implementation.


Education
---------

1998-2000
:   **PhD, Electrical Engineering**; University Of Illinois at Urbana-Champaign

    *Thesis title: Fast Algorithms for Tomography*

1995-1998
:   **MS, Electrical Engineering**; University of Illinois at Urbana-Champaign

    *Thesis title: Tomography with Unknown View Angles*

1991-1995
:   **BS, Electrical Engineering**; University of Delaware

    *Thesis title: Multichannel Permutation Filters*


Skills
------

- Leadership of multidisciplinary technical teams
- Invention and creative problem solving
- System analysis and design
- Software and system architecture
- Machine learning algorithm development
- Cloud architecture, IoT, server-less functions
- Signal processing algoirithm development
- PCB design
- Software/firmware technology development (Rust/C++/C/Python/Verilog)
- Inverse problems
- Application specific data compression


Technical Experience
--------------------

John Crane Sense
: (Lead system designer, architect, electrical engineer)
Architected, Designed and lead the implementation of a continuous,
multichannel data acquisition system for monitoring assets in industrial 
settings.  It featured:

    - Multichannel mega-sample/sec analog channels
    - Static channels (1Hz) for collecting slowly varying signals
    - Modular internal design to allow for different sensor configurations
    - Embedded FPGA processing for data reduction and communication with the embedded processor
    - Real time signal processing
    - Cloud side data processing, and time series storage

Sense Cloud
: (Architect, lead developer)
Architected and implemented a cloud-agnostic system that runs on Kubernetes to
store, index and analyze large volumes of telemetry data coming from custom 
data acquisition systems.

Ice9
: (Hardware, Firmware, Software engineer)
Architected, designed and implemented an FPGA co-processor board for industrial
temperature applications.

    - Component selection
    - Schematic capture
    - PCB layout (6-layer, thru-hole vias, 381-BGA part)
    - Firmware design and implementation (including a custom SDRAM controller)
    - C API to communicate to the FPGA via USB using streaming communications
    - Rust CLI to test the board

EDS
: (Lead system designer and architect, Imaging scientist) 
Designed the explosives detection system (CTX5800 and much of the
architecture of the CTX9800 SEIO) systems

    - System geometry design and optimization
    - Detailed simulations of the imaging and radiation shielding performance
    - Electrical architecture
    - Anti-scatter design
    - Data processing chain (image processing, signal corrections, scatter mitigation, etc.)

Eclipse
: (Lead designer and architect)
The Eclipse computed tomography detector system - a fully owned 
design that included a tile-able design for modularity, cost efficiency
and high performance.

FlatPak DB
: (Primary inventor and developer)
 Flatpak (internal to Smiths) - a high performance, large volume
time series database with best in class indexing performance, an
easy-to-use REST interface.  Written in Rust.

Intellifuse
: (Lead developer and software architect)
A smart infusion system for Smiths Medical - a multi-processor,
efficient and elegant software stack to deliver a complex user interface
and tight coupling to safety and control functions provided by an
embedded co-processor.

CT Recon
: (Developer)
Developed several novel and patented algorithms for correcting CT-induced
artifacts in images, including those from beam hardening effects, scattered
radiation, imperfect anti-scatter grid geometry, etc.

Open Source
-----------

[**RustHDL**](https://github.com/samitbasu/rust-hdl)
: Sole developer - 
A completely new framework for describing FPGA firmware
using the Rust programming language.  Offers type safety, static analysis
and high performance simulation of designs from the comfort of a Rust 
environment.  

[**SPARQ**](https://github.com/smithsdigitalforge/sparq)
: Sole developer and architect - 
An infrastructure library for mechatronics in C++.  SPARQ is a core technology behind smart infusion systems.

[**FreeMat**](http://freemat.sourceforge.net)
: Sole developer - 
FreeMat is a free and open source environment for rapid engineering and scientific prototyping and data processing.  FreeMat’s mission was to democratize access to signal, image and data processing to advance science and technology.  It has been downloaded at least 1 million times on 4 different platforms, and is in use around the world.

Certifications
--------------

- Advanced PCB Layout, Fedevel Academy
- Power supply design and Layout, Fedevel Academy
- Learn Altium essentials, Fedevel Academy
- Six Sigma Green Belt, GE

Awards
------

2011
CEO award, safran morpho detection
Innovation

2011
Dushman award, GE Global Research
Technical achievement with significant business impact
VEO

2008
University of Illinois young alumni achievement award

2007
Technologist of the week, GE

2006
Edelheight award, GE global research
imaging technologies
vuepoint recon

2001
IEEE young author best paper award

1999, 2000
Mac Van Valkenburg fellow

1996-1999
Joint Services Electronics Program fellow

1991-1995
Eugene DuPont scholar


Hobbies
-------

- Lead Singer (Rock/Pop cover bands)
    - Mark's Marauders
    - Excess Baggage

- Cooking, Hiking, Weight Lifting, Electronics Design, Open-Source Coding, Rust


Patents (U.S. Only)
-------

1.  10,969,515      Contactless data communication in CT systems
2.  10,302,774      Detector assembly for use in CT imaging systems
3.  10,288,762      Systems and methods for detecting luggage in an imaging system
4.  10,264,263      Systems and methods for compressing image data generated by a computed tomography (CT) imaging system
5.  10,182,777      Open drum gantry for computed tomography system
6.  10,094,950      System and method for detecting and reconstructing objects in a non-continuous stream of items in an imaging system
7.  10,076,294      Gantry system with support wheels
8.  10,058,293      Detector assemblies and methods for helical CT scanning
9.  10,034,361      Line-frequency rotary transformer for computed tomography gantry
10. 10,010,296      Systems and methods for x-ray CT scanner with reconfigurable field of view
11. 9,804,290       Cross-correlated gamma ray and neutron detector
12. 9,618,462       Systems and methods for imaging and determining a signature of an object
13. 9,417,340       Compact geometry CT system
14. 9,405,990       X-ray diffraction imaging system with signal aggregation across voxels containing objects and method of operating the same
15. 9,134,258       Systems and methods for imaging and detecting sheet-like material
16. 8,953,902       Systems and methods for thin object imaging
17. 8,768,032       Method for correction of artifacts from edge detectors in compact geometry CT
18. 8,571,287       System and method for iterative image reconstruction
19. 8,416,415       Gas turbine optical imaging system
20. 8,254,656       Methods and system for selective resolution improvement in computed tomography
21. 8,233,682       Methods and systems for improving spatial and temporal resolution of computed images of moving objects
22. 8,180,139       Method and system for inspection of containers
23. 8,180,138       Method and system for inspection of containers
24. 8,175,115       Method and system for iterative reconstruction
25. 8,160,200       Method and system for image data acquisition
26. 8,111,889       Method and apparatus for efficient calculation and use of reconstructed pixel variance in tomography images
27. 8,111,803       Method for energy sensitive computed tomography using checkerboard filtering
28. 8,081,733       Method and systems for scanning a stream of objects
29. 8,027,427       Systems and method for scanning a continuous stream of objects
30. 7,889,835       System and method for detecting an object by dynamically adjusting computational load
31. 7,885,375       Method and system for X-ray imaging
32. 7,881,426       Method and system for performing a scan of an object
33. 7,852,979       Dual-focus X-ray tube for resolution enhancement and energy sensitive CT
34. 7,844,030       System and method of fast switching for spectral imaging
35. 7,835,486       Acquisition and reconstruction of projection data using a stationary CT geometry
36. 7,813,473       Method and apparatus for generating temporally interpolated projections
37. 7,760,848       Method and system for generating a multi-spectral image of an object
38. 7,706,499       Acquisition and reconstruction of projection data using a stationary CT geometry
39. 7,696,483       High DQE photon counting detector using statistical recovery of pile-up events
40. 7,639,775       Method and system for imaging using multiple offset X-ray emission points
41. 7,639,774       Method and apparatus for employing multiple axial-sources
42. 7,606,347       Photon counting x-ray detector with overrange logic control
43. 7,551,708       Method of iterative reconstruction for energy discriminating computed tomography systems
44. 7,492,855       System and method for detecting an object
45. 7,477,771       Method and system for extracting information about the cardiac cycle from CT projection data
46. 7,466,793       Distinct incident energy spectra detection
47. 7,433,443       System and method of CT imaging with second tube/detector patching
48. 7,428,292       Method and system for CT imaging using multi-spot emission sources
49. 7,396,162       Scatter correction for CT method and apparatus
50. 7,386,088       Method and system for iterative image reconstruction
51. 7,382,852       Method and apparatus for correcting motion in image reconstruction
52. 7,379,525       Method and system for efficient helical cone-beam reconstruction
53. 7,376,255       System and method for image reconstruction
54. 7,372,934       Method for performing image reconstruction using hybrid computed tomography detectors
55. 7,366,279       Scatter control system and method for computed tomography
56. 7,362,843       System and method for reconstruction of cone beam tomographic projections with missing data
57. 7,356,174       Contraband detection system and method using variance data
58. 7,333,587       Method and system for imaging using multiple offset X-ray emission points
59. 7,283,604       Method and system of CT data correction
60. 7,280,631       Stationary computed tomography system and method
61. 7,260,170       Method and system of CT data correction
62. 7,254,209       Iterative CT reconstruction method using multi-modal edge information
63. 7,242,749       Methods and systems for dynamic pitch helical scanning
64. 7,227,982       Three-dimensional reprojection and backprojection methods and algorithms for implementation thereof
65. 7,227,923       Method and system for CT imaging using a distributed X-ray source and interpolation based reconstruction
66. 7,221,728       Method and apparatus for correcting motion in image reconstruction
67. 7,215,731       Fast backprojection/reprojection with hexagonal segmentation of image
68. 7,203,267       System and method for boundary estimation using CT metrology
69. 7,082,180       Methods and apparatus for computing volumetric perfusion
70. 7,054,409       Volumetric CT system and method utilizing multiple detector panels
71. 7,016,456       Method and apparatus for calibrating volumetric computed tomography systems
72. 6,937,689       Methods and apparatus for image reconstruction in distributed x-ray source CT systems
73. 6,862,335       System and method for iterative reconstruction of cone beam tomographic images
74. 6,754,300       Methods and apparatus for operating a radiation source
75. 6,724,856       Reprojection and backprojection methods and algorithms for implementation thereof
76. 6,625,249       Method, system and program product for tomographic backprojection using multi-color rendering engine
77. 6,597,756       Methods and apparatus for multi-slice image reconstruction
78. 6,351,548       Fast hierarchical reprojection algorithm for tomography
79. 6,332,035       Fast hierarchical reprojection algorithms for 3D radon transforms
80. 6,307,911       Fast hierarchical backprojection for 3D Radon transform
81. 6,282,257       Fast hierarchical backprojection method for imaging


Journal Publications
--------------------

- B. De Man and S. Basu, “Distance-Driven Projection and Backprojection: Extensions to Three Dimensions and Analysis,” Phys. Med. Biol., 2004.
- R. Gupta, S. Bartling, S. Basu, W. Ross, H. Becker, A. Pfoh, T. Brady, and H. Curtin, “Experimental Flat-Panel High-Spatial Resolution Volume CT of the Temporal Bone,” American Journal of Neuroradiology, 2004.
- A. Katsevich, S. Basu and J. Hsieh, “Exact Filtered Backprojection Reconstruction for Dynamic Pitch Helical CT,” Phys. Med. Biol., 2004.
- S. Basu and Y. Bresler, “O(N3 log N) Backprojection Algorithm for the 3D Radon Transform,” IEEE Trans. Medical Imaging, 2002.
- S. Basu and Y. Bresler, “An Empirical Study of Minimax-Optimal Fractional Delays for Lowpass Signals,” IEEE Trans. Circuits Syst. II, 2002.
- S. Basu and Y. Bresler, “Error Analysis and Performance Optimization in Fast Hierarchical Backprojection Algorithms,” IEEE Trans. Image Proc., 2001.
- S. Basu and Y. Bresler, “Uniqueness of Tomography with Unknown View Angles,” IEEE Trans. Image Proc., 2000.
- S. Basu and Y. Bresler, “Feasibility of Tomography with Unknown View Angles,” IEEE Trans. Image Proc., 2000.
- S. Basu and Y. Bresler, “Stability of Nonlinear Least Squares Problems and the Cramer-Rao Bound,” IEEE Trans. Signal Proc., 2000.
- S. Basu and Y. Bresler, “A Global Lower Bound on Parameter Estimation Error with Periodic Distortion Functions,” IEEE Trans. Inf. Theory, 2000.
- S. Basu and Y. Bresler, “O(N2 log2 N) Filtered Backprojection Reconstruction Algorithm for Tomography,” IEEE Trans. Image Proc., 2000.


Selected Conference Publications
--------------------------------

- S. Basu, and B. DeMan, “Fast and accurate scatter estimation,” SPIE EI 2007.
- S. Basu, et al., “Experimental System for Investigating Novel CT Geometries,” MIC 2007.
- B. De Man, S. Basu, and B. Grekowicz, “A comparison between two exact wide-cone helical reconstruction algorithms,” RSNA 2004.
- A. Katsevich, S. Basu, and J. Hsieh, “Exact Dynamic Pitch Wide Cone Helical Reconstruction,” MIC 2004.
- B. De Man and S. Basu, “A study of noise and spatial resolution for 2D and 3D filtered backprojection reconstruction,” MIC 2004.
- B. De Man and S. Basu, “3D Distance-driven Projection and Backprojection,” Seventh Int. Conf. on Fully 3D Reconstruction in Radiology and Nuclear Medicine, St. Malo, 2003.
- P. Edic, S. Basu, A. Pfoh, J. McLeod, W. Ross, “Performance Results from Pre-Clinical Flat-panel-based Volumetric CT Systems,” RSNA 2002.
- P. Edic, B. De Man, and S. Basu, “Phase-Weighted Sparse-view Iterative Reconstruction for Cardiac CT,” Annual Meeting of the European Congress of Radiology, Vienna, Austria, 2003.
- P. Edic, S. Basu, B. De Man, et al. , “Preliminary Investigations of Dynamic Imaging Utilizing Volumetric CT,” Annual Meeting of the European Congress of Radiology, Vienna, Austria, 2003.
- S. Bartling, R. Gupta, T. Rodt, S. Basu, et al., “Experimental results: volume-CT (VCT) could overcome CT limitations in cochlea implant imaging,” Seventeenth Symposium Neuroradiologicum, Paris, France, 2002.
- B. De Man and S. Basu, “Distance-driven projection and backprojection for computed tomography,” MIC 2002.
- M. Mattiuzzi, J. LeBlanc, S. Basu, et al., “A computed tomography virtual reality testbed,”
Proc. IEEE Nuc. Sci. Symp. Med. Im. Conf. 2001.
- M. Rosol, A. Pfoh, S. Basu, et al., “Volume CT in Carotid Atherosclerosis,” Second Intl. Workshop on Coronary MR and CT Angiography, Chicago, IL, 2001.

----

> <basu.samit@gmail.com> • +1 (518) 466-4416\
> Fremont, CA USA
