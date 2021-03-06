.. _firmware_quickstart:

Firmware Quickstart
-------------------

Install the dependencies
^^^^^^^^^^^^^^^^^^^^^^^^
To compile and to run the project, some dependencies need to be installed :

  * ARM cross-compilation toolchain
  * make  

Fetch the firmware sources
^^^^^^^^^^^^^^^^^^^^^^^^^^
The sources can be fetched from LEIA github : 

.. code:: bash

   $ git clone git@github.com:h2lab/leia-solo-firmware.git
   $ cd leia-solo-firmware

Compile the firmware
^^^^^^^^^^^^^^^^^^^^^^^^^
Once the dependencies are installed and the sources fetched, it is possible to build a firmware with the following 
commands : 

.. code:: bash

   $ make firmware
