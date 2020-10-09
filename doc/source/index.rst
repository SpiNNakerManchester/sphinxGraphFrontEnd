SpiNNaker Graph Front End
=========================

These pages document the main Manchester python code for the SpiNNakerGraphFrontEnd branch of the SpiNNaker_ Project which can be found on github_

Alternative ways to run SpiNNaker_ are using PyNN_ or the older PyNN_07_ .

.. _SpiNNaker: http://apt.cs.manchester.ac.uk/projects/SpiNNaker/
.. _github: https://github.com/SpiNNakerManchester
.. _PyNN_ http://spinnaker8manchester.readthedocs.io/en/latest/index.html
.. _PyNN_07: http://spinnaker7manchester.readthedocs.io/en/latest/index.html

SpiNNUtils
----------
This provides basic utility functions and classes to other parts of SpiNNaker's tooling. Nothing in here knows anything about SpiNNaker functionality.

.. toctree::
   :maxdepth: 3

   spinn_utilities_index

SpiNNUtils_github_

SpiNNUtils_individual_docs_

.. _SpiNNUtils_github: https://github.com/SpiNNakerManchester/SpiNNUtils
.. _SpiNNUtils_individual_docs: http://spinnutils.readthedocs.io

SpiNNMachine
------------
This package is used to provide a Python representation of a SpiNNaker machine

.. toctree::
   :maxdepth: 3

   spinn_machine_index

SpiNNMachine_github_

SpiNNMachine_individual_docs_

.. _SpiNNMachine_github: https://github.com/SpiNNakerManchester/SpiNNMachine
.. _SpiNNMachine_individual_docs: http://spinnmachine.readthedocs.io


PACMAN
------
This package provides utilities for partitioning, placing a routing on a SpiNNaker machine

.. toctree::
   :maxdepth: 3

   pacman_index

PACMAN_github_

PACMAN_individual_docs_

.. _PACMAN_github: https://github.com/SpiNNakerManchester/PACMAN
.. _PACMAN_individual_docs: http://pacman.readthedocs.io


SpiNNMan
--------
This package provides utilities for interacting with a SpiNNaker machine.

.. toctree::
   :maxdepth: 3

   spinnman_index

SpiNNMan_github_

SpiNNMan_individual_docs_

.. _SpiNNMan_github: https://github.com/SpiNNakerManchester/SpiNNMan
.. _SpiNNMan_individual_docs: http://spinnman.readthedocs.io


DataSpecification
-----------------
This package provides utilities for specifying binary data algorithmically, and executing the specifications to produce the data.

.. toctree::
   :maxdepth: 3

   data_specification_index

DataSpecification_github_

DataSpecification_individual_docs_

.. _DataSpecification_github: https://github.com/SpiNNakerManchester/DataSpecification
.. _DataSpecification_individual_docs: http://dataspecification.readthedocs.io

SpiNNFrontEndCommon
-------------------
This package provides functionality which are common to front ends that translate application level programs into executables which run on a SpiNNaker machine.

.. toctree::
   :maxdepth: 3

   spinn_front_end_common_index

SpiNNFrontEndCommon_github_

SpiNNFrontEndCommon_individual_docs_

.. _SpiNNFrontEndCommon_github: https://github.com/SpiNNakerManchester/SpiNNFrontEndCommon
.. _SpiNNFrontEndCommon_individual_docs: http://spinnfrontendcommon.readthedocs.io

SpiNNakerGraphFrontEnd
----------------------
This package provides a Graph Front End implementation for SpiNNaker.

.. toctree::
   :maxdepth: 3

   spinnaker_graph_front_end_index

SpiNNakerGraphFrontEnd_github_

SpiNNakerGraphFrontEnd_individual_docs_

.. _SpiNNakerGraphFrontEnd_github: https://github.com/SpiNNakerManchester/SpiNNakerGraphFrontEnd
.. _SpiNNakerGraphFrontEnd_individual_docs: https://readthedocs.org/projects/spinnakergraphfrontend/

spalloc
-------
Spalloc is a Python library and set of command-line programs for requesting SpiNNaker machines from a spalloc server.

The spalloc module uses a different documentation style so is not included here.

Their documenation can be found at: spalloc_readthedocs_

spalloc_github_

.. _spalloc_github: https://github.com/SpiNNakerManchester/spalloc
.. _spalloc_readthedocs: http://spalloc.readthedocs.io

spalloc_server
--------------
A SpiNNaker machine management application which manages the partitioning and allocation of large SpiNNaker machines
into smaller fragments for many simultaneous users.

The spalloc_server module uses a different documentation style so is not included here.

Their documenation can be found at: spalloc_server_readthedocs_

spalloc_server_github_

.. _spalloc_server_github: https://github.com/SpiNNakerManchester/spalloc_server
.. _spalloc_server_readthedocs: http://spalloc-server.readthedocs.io


Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
