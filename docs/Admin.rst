
Administation
========

Useful dode snippets
--------

Install the package with pip::

    $ pip install read-the-docs-template

Mounting researchdata share::

    $ USER=UCT_login mount /scratch/researchdata_mri

Freeurfer and copying os symbolic links::

    $ cp -rL 'from' 'to'

where: -r recursive, -L dereference (i.e. file in the source tree will be copied to a regular file in the destination tree).

Port splitting on Mellanox switch
-------

ssh to the switch::

    Do you want to use the wizard for initial configuration? n
    switch-f66e1c [standalone: master] > enable
    switch-f66e1c [standalone: master] # configure terminal
    switch-f66e1c [standalone: master] (config) # show interfaces ethernet status
    switch-f66e1c [standalone: master] (config) # interface ethernet 1/19 shutdown
    switch-f66e1c [standalone: master] (config) # int ethernet 1/19
    switch-f66e1c [standalone: master] (config interface ethernet 1/19) # module-type qsfp-split-4
      > the following interfaces will be unmapped: 1/19
      > Type 'YES' to confirm split: YES
    switch-f66e1c [standalone: master] (config) # show interfaces ethernet status
    switch-f66e1c [standalone: master] (config) # q
    switch-f66e1c [standalone: master] (config) # exit
    switch-f66e1c [standalone: master] # exit


Installation1
----------------

Install the package with pip::

    $ pip install read-the-docs-template

Table
------------

sdfsfs



Installation2
~~~~~~~~~~

Install the package with pip::

    $ pip install read-the-docs-template

Table of contents options
-------------------------

sdfsfs
