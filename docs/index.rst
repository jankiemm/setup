.. Read the Docs Template documentation master file, created by
   sphinx-quickstart on Tue Aug 26 14:19:49 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

CUBIC server repository
==================================================

This page is intended to assist researchers with running jobs on our cluster.
There are 24 nodes in in the partition (RomanEmpire), they are called rome0[01-24]. Each of the nodes is powered by EPYC Rome CPU with 64 cores (128 threads) clocked at 2GHz. Each node has 512GB of memory and 2TB oh HD space (where the software resides). The calculations are done in user's directory /scratch/username which is a shared 80TB NFS.

Relevant Software: AFNI (latest version, updated weekly), Freesurfer 6.0.1, Infant Freesurfer , FSL 5.0.10, TORTOISE 3.1.0-3.1.2, SPM12, Matlab 2018a, R 3.6.3I can install new version of Freesurfer and FSL.

Contents2e (check):

.. toctree::
   :maxdepth: 2
   
   authors.rst
   
   
   .. code-block:: bash
   :linenos:

   for i in 1 to 24
    do
    parallel
    done
