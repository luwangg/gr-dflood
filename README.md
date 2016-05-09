#  Flooding-based UnderwaterAcoustic Communication Protocol (DFLOOD) Implementation for GNU Radio

The module implements the protocol originally described in:
R. Otnes and S. Haavik, "Duplicate reduction with adaptive backoff for a flooding-based underwater network protocol," OCEANS - Bergen, 2013 MTS/IEEE, Bergen, 2013, pp. 1-6.
and:
A. Komulainen and J. Nilsson, "Capacity improvements for reduced flooding using distance to sink information in underwater networks," Underwater Communications and Networking (UComms), 2014, Sestri Levante, 2014, pp. 1-5. 

# Copyright 2016 Michel Barbeau, Carleton University.
# Version: April 25, 2016

## Installing 

`git clone https://github.com/michelbarbeau/gr-dlood`

## Building


```
cd gr-dflood

mkdir build

cd build 

cmake ../

make

sudo make install

sudo ldconfig

```

## Running

To run within gnuradio-companion

Open the flow graph  gr-dflood/examples/loopback.grc

To run outside gnuradio-companion

cd gr-dflood/examples

python top_block.py
