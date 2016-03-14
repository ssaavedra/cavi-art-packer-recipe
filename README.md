CAVI-ART Packer Recipe
======================

This is the repository for a Packer recipe for building a virtual machine with CAVI-ART VA-related tools.

CAVI-ART is a project partially funded by the Spanish Government.

Compilation
===========

1. You need to grab the fedora-base.ova file from https://drive.google.com/open?id=0B9pkXRNr2fviak1PNVcxMkkwd3c
2. Build the image with `packer build --only=virtualbox-ovf template.json`


Usage
=====

The image is readily available as a Vagrant machine for VirtualBox as [`ssaavedra/cavi-art`][atlas].

It is also available as an OVA at https://drive.google.com/open?id=0B9pkXRNr2fviUm0wRVp2OXc0WEE

  [atlas]: https://atlas.hashicorp.com/ssaavedra/boxes/cavi-art
