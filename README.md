# Presentation on Jupyter OOMMF at PyConDE & PyData 2018

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/fangohr/talk-pyconde-2018/master)

To follow the live demo, please go to
https://mybinder.org/v2/gh/fangohr/talk-pyconde-2018/master, or click
the "launch binder" button above.

The slides of the talk are [available here (pdf)](slides.pdf).

## Abstract

See https://de.pycon.org/schedule/talks/driving-simulation-and-data-analysis-of-magnetic-nanostructures-through-jupyter-notebook/

Reproduced below:

### Title

Driving simulation and data analysis of magnetic nanostructures through Jupyter Notebook

### Brief summary

We present ongoing work from a project that makes a particular
computer simulation (implemented in C++ and Tk/Tcl) accessible through
a Python interface, and through the Jupyter Notebook. The talk
describes the motivation, benefits and current status of the project.

Tags: Data Science, Jupyter, Programming, Python, Science

### Speaker

Hans Fangohr (@ProfCompMod)

Hans Fangohr is a Data Analysis Scientist at the European XFEL GmbH
(which hosts the worlds most brilliant X-Ray Free Electron Laser,
http://xfel.eu) and Professor of Computational Modelling at the
University of Southampton. He received his undergraduate degree
"Diplomphysiker" in physics from the University of Hamburg (Germany)
and completed his PhD studies in the High Performance Computing Group
at the department of Computer Science in Southampton. He is a full
professor since 2010, and specialised in computational science, data
analysis and software engineering for science.

### Description

We present ongoing work from a project that makes a particular
computer simulation (implemented in C++ and Tk/Tcl) accessible through
a Python interface, and through the Jupyter Notebook. The talk
describes the motivation and current status of the project.

In more detail, the computer simulation in question is the Object
Oriented Micromagnetic Modelling Framework (OOMMF) which is likely the
most widely used micromagnetic simulation package. It can be driven
through a graphical (Tk) user interface or through a configuration
file that defines a simulation run.

In this talk, we first show a Python interface to OOMMF that allows
the driving of OOMMF simulations from a Python program or interpreter
prompt. This way we embed a widely used scientific code from 1990s in
a general purpose programming language [1] and enable the full use of
the ecosystem of scientific libraries available for Python. For
example, design optimisation, specialised post-processing, and the
creation of figures can all be carried out using a single script;
making the work more easily reproducible.

Second, we integrate the Python interface to OOMMF into a Jupyter
notebook, so that all existing benefits of using Jupyter are inherited
for the use in computational micromagnetics, which is the reason we
named our code Jupyter-OOMMF (JOOMMF). A JupyterHub installation of
the tool reduces barriers in uptake, and all the code is on github.

We discuss the benefits of driving computer simulation and data
analysis through Jupyter Notebooks.

This project is a part of the Jupyter-OOMMF (JOOMMF) activity in the
OpenDreamKit project and we acknowledge financial support from Horizon
2020 European Research Infrastructures project (676541). The work is
also supported by the EPSRC CDT in Next Generation Computational
Modelling EP/L015382/1, and the EPSRC grants EP/M022668/1 and
EP/N032128/1.

For additional context: micromagnetic modelling is a key research
method in academia and industry to support development of
high-capacity magnetic storage devices that are cheap, fast, and
reliable, and to enable research into future alternative storage and
processing technologies such as spintronics. The OOMMF modelling
package has been used in over 2500 publications since 1999.

[1] Beg, M., Pepper, R. A., and Fangohr, H. User interfaces for
computational science: A domain specific language for OOMMF embedded
in Python. AIP Advances 7, 056025 (2017),
https://doi.org/10.1063/1.4977225
