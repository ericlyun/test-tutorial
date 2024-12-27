
AHS: An EDA toolbox for Agile Chip Front-end Design
============================

.. figure:: images/system.png
    :align: center
    :figwidth: 1000px

Overview
--------

As Moore’s law is approaching to the end, designing specialized hardware along with the software that map the applications onto the specialized hardware is a promising solution. The hardware design determines the peak performance, while the software is also important as it determines the actual performance. Hardware/software (HW/SW) co-design can optimize the hardware acceleration and software mapping in concert and improve overall performance. However, the current flow designs hardware and software in isolation. More importantly, both hardware and software are difficult to design and optimize due to the low level programming and huge design space.

In this tutorial, we present AHS, an Agile framework for Hardware specialization and Software mapping for tensor applications. Given a tensor application described using high level language, AHS can automatically define the interfaces between the hardware and software, navigate the huge design space synergistically, and automatically generate the hardware implementation and software mapping. AHS consists of several components and each component comes with an open source tool. First, we introduce HASCO [ISCA’21], a tool for hardware and software co-design. HASCO uses a matching approach based on a loop-based IR to explore different HW/SW partitioning methods. HASCO employs different DSE algorithms for hardware and software due to different design goals and evaluation costs. Second, we introduce TENET [ISCA’21], a tool for hardware dataflow notation and performance model. TENET can cover the design space of hardware dataflows completely using relation-centric notation. Third, we introduce TensorLib [DAC’21], the synthesis backend for TENET. TensorLib can automatically generate the hardware dataflow implementation written in Chisel. Finally, we introduce Flextensor [ASPLOS’20], a tool for automatic software mapping and optimization. Flextensor can automatically generate optimized software implementation for various hardware platforms including CPUs, GPUs, FPGAs, and ASICs. 

Schedule
--------

Organizers
----------

Related papers
--------------

Git Repos
---------

.. toctree::
   :maxdepth: 2
   :caption: Contents:

