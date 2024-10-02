This folder contains the resources used in our implementation. Specifically:

* ``notebook`` is a folder containing the jupyter notebooks of our implementation: the ``packet_modifier.ipynb``, the ``ML_experiments.ipynb``, and ``statistical_tests.ipynb``; we also report the ``snippet`` subfolder, containing a small PCAP trace, used to test the ``packet_modifier.ipynb``.
* ``results`` is a folder containing our complete results (i.e., the output of each "trial"); it can be used to run the ``statistical_tests.ipynb``.

We also report the two configuration files of Argus (``ra.conf`` and ``argus2.conf``), used to extract the NetFlows from a given PCAP trace; as well as the ``requirements.txt`` file (for the notebooks above).

## Data

We cannot release the entire dataset we used (due to copyright reasons, but also size and privacy). However, we used public data from the [MCFP](https://mcfp.felk.cvut.cz/publicDatasets/) repository, so it is possible to download the PCAP traces, apply our PacketModifier, extract the NetFlows, and run our experiments. 

We will release our data _upon request_ and **if** the original files are deleted/taken-down by the creators of MCFP.
