.. tRIBS Docs documentation master file, created by
   sphinx-quickstart on Thu Apr  9 15:33:28 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


tRIBS Documentation
======================

**Foreword**


    The **tRIBS (TIN-based Real-Time Integrated Basin Simulator)
    Distributed Hydrologic Model** is a set of object-oriented,
    *C++* programs that allow for the construction and simulation
    of catchment scale hydrologic processes on a *Triangulated
    Irregular Network (TIN)*. The development of the tRIBS Model
    has been the result of hydrologic modeling and software
    development efforts performed by various researchers in the
    Ralph M. Parsons Laboratory in the Department of Civil and
    Environmental Engineering of the Massachusetts Institute of
    Technology. Model development continues at MIT and New Mexico Tech,
    among other partnering institutions. This document is intended
    to serve as a user manual for the tRIBS Model, including instructions
    on how to download, compile, set up and run tRIBS. In addition,
    an effort has been made to document the model software design using
    class and workflow diagrams. This guide assumes that the reader is
    familiar with the capabilities of the tRIBS Model and its intended
    purposes. More information concerning the model can be obtained
    through the tRIBS Research Description and Publication List.

    Additional instructions regarding the Mesh Generation can be
    found in the `CHILD Model User Manual <https://github.com/childmodel/child/blob/master/Child/Docs/child_users_guide.pdf/>`_.

    tRIBS is copyrighted 2000-2021 by Enrique R. Vivoni, Valeri Y. Ivanov, Rafael L. Bras
    and Dara Entekhabi and may not be used for commercial purposes without written consent from the authors.


        .. figure::  images/hydrocycle.png
          :width: 400
          :alt: tRIBS Distributed Hydrologic Model System
          :align:   center


    The **TIN-based Real-time Integrated Basin Simulator (tRIBS)**, is fully
    distributed model of hydrologic processes.


**What type of processes does tRIBS model?**


    The *tRIBS* model description can be found in [Ivanov_2004a]_, [Ivanov_2004b]_ and [Vivoni_2004]_.

    We mention a few *tRIBS* processes it models:

        - Couple the vadose and saturated zones with the dynamic water table.
        - Moisture infiltration waves.
        - Soil moisture redistribution.
        - Topography-driven lateral fluxes in the vadose and groundtable zones.
        - Computes the radiation and energy balance.
        - Interception, evaporation and evapotranspiration.
        - Hydrologic and hydraulic routing.
        - other.


.. [Ivanov_2004a] Ivanov, V.Y., Vivoni, E.R., Bras, R.L. and Entekhabi, D. 2004a. Catchment Hydrologic
   Response with a Fully-Distributed Triangulated Irregular Network Model. Water Resources Research. 40(11): W11102.
.. [Ivanov_2004b] Ivanov, V.Y., Vivoni E.R., Bras, R.L. and Entekhabi, D. 2004b. Preserving high-resolution
   surface and rainfall data in operational-scale basin hydrology: A fully-distributed, physically-based
   approach. Journal of Hydrology. 298(1-4): 80-111
.. [Vivoni_2004] Vivoni, E. R., Ivanov, V. Y., Bras, R. L. & Entekhabi, D. (2004). Generation of triangulated
   irregular networks based on hydrological similarity.Journal of Hydrologic Engineering, 9(4), 288–302.

------------------------------------------------------------------------------------

..  toctree::
    :maxdepth: 3
    :numbered:
    :caption: TABLE OF CONTENTS

    man/Introduction.rst
    man/Model_Design.rst
    man/Model_Input_Formats.rst
    man/Model_Execution.rst
    man/Terrain_Analysis_for_Model_Setup.rst
    man/Hydrometeorological_Data_Processing.rst
    man/Contacts_Further_Readings.rst



..  toctree:
    :maxdepth:  2

  * :ref:`genindex`
  * :ref:`modindex`
  * :ref:`search`


----------------------------------------------------------

    *Last update:* C. Lizarraga, 01/30/2021
