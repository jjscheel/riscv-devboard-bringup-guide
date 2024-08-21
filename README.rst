RISC-V DevBoard Bringup Guide
============================

This is the repository for the `RISC-V Developer Board Bringup Guide (TBD URL), an introductory material prepared by RISC-V International.  
It was forked from a legacy project (archived) `The RISC-V Getting Started Guide <https://github.com/riscvarchive/risc-v-getting-started-guide>`_

For details about RISC-V itself, see the `RISC-V Website <https://riscv.org>`_.

You can contribute to the Bringup Guide too!
We are always happy to add more platforms and examples, and make the Guide more attractive to readers.
See `Contributing`_ below for details.

Compiling the Guide
-------------------

The Guide is built using Sphinx, a popular documentation framework used e.g. by Python, Zephyr and Linux, based on reStructuredText.

Sphinx can be installed with ``pip``, the Python package manager::

    pip install sphinx

(for detailed instructions, see `Installing Sphinx <http://www.sphinx-doc.org/en/master/usage/installation.html>`_)

To compile the HTML version of the Guide, use::

    make html

The output will reside in the ``build/`` directory.

You can also generate a PDF, which requires TeX and a few other tools.

Contributing
------------

The RISC-V ecosystem is largely based around a diversified pool of corporate and personal contributions coming from over 130 corporate members and thousands of developers around the world.
We especially welcome contributions that make RISC-V more accessible to the broader public (such as improving this Guide) - and we are happy you are reading this!

Please use the GitHub issues and pull requests mechanisms to contribute to the Guide.
This may include:

* guides for new platforms (please follow the style in which existing platforms are written)
* corrections and extensions to existing platforms
* more advanced pieces of content showcasing additional software that can be run on RISC-V

Note that in order to keep the material universally accessible, please only contribute guides based on software that is freely available without unnecessary limitation.

New platform contributions should be **complete and tested** on multiple platforms (or at least explicitly marked as incomplete in some aspects), so that users can get started successfully without running into problems.

For the sake of clarity, legibility and user-friendliness, the RISC-V Foundation reserves the right to modify or refuse to include submitted pieces of content at its discretion.
