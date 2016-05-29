sa-gluster-fs
=============

[![Build Status](https://travis-ci.org/softasap/sa-gluster-fs.svg?branch=master)](https://travis-ci.org/softasap/sa-gluster-fs)

Installs basic gluster fs server package.

GlusterFS is a scalable network filesystem. Using common off-the-shelf hardware, you can create large, distributed storage solutions for media streaming, data analysis, and other data- and bandwidth-intensive tasks. GlusterFS is free and open source software.


Example of usage (all parameters are optional)

Simple

  roles:
    - {
        role: "sa-gluster-fs"
      }


Advanced:


  roles:
    - {
        role: "sa-gluster-fs",
        glusterfs_version: "3.7"
      }




