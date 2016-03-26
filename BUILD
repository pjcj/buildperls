#!/bin/sh

rm -rf tmp/perl
./brewbuild_all
sudo ./mklinks $PERLBREW_ROOT
./runcpan
rm -rf tmp/perl
