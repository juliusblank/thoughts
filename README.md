# thoughts
Collecting all kinds of ideas

## VMs / Cloud

* running virtualbox on a digitalocean droplet does not work. at least i could not get it running after six hours trying to get hashicorp's otto going on a droplet. probably stupid setup anyway...

## Unix

### commandline tips

* Unpack a downloaded .tar.gz with an annoying subfolder and repack it without the folder

    tar xvf mysql-5.5.15-linux2.6-i686.tar
    rm mysql-5.5.15-linux2.6-i686.tar
    tar cvf mysql-5.5.15-linux2.6-i686.tar -C mysql-5.5.15-linux2.6-i686 .
