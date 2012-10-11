du human readable
=================

duh is a python script replicating and extending the functionality of the unix command::

    du -hsc * .[^.]* | sort -h

Place ``.duh`` in your home directory and add an alias

Bash: add to your ``~/.bashrc``::
    
    alias duh='~/.duh'

TCSH: add to your ``~/.tcshrc``::
    
    alias duh '~/.duh'

Example output is::

    Under this directory:
     Size  No. files  Name
      16B          1  a_file.py
     34KB          1  e_file.sh
     69MB         17  c_dir
    567MB          1  b_file.log
      4GB        235  d_dir

    This directory:
    3 files,   2 directories,   0 links

    This directory and subdirectories:
    255 files,   12 directories
    Total size: 5GB 

