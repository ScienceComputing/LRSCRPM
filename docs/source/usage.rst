Usage
=====

.. _installation:

Installation
------------

To use BLAZE, first download it using wget and decompress it using unzip:

.. code-block:: console

   wget https://github.com/shimlab/BLAZE/releases/download/v1.1.0/BLAZE_v1.1.0.zip
   unzip BLAZE_v1.1.0.zip

Generating the putative barcode and barcode whitelist
----------------

.. code-block:: console
   pip install Biopython pandas numpy tqdm matplotlib levenshtein
   python3 blaze.py --expect-cells=1000 --threads=20 path/to/fastq_pass


