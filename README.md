iCelera eeg binary parser
=========================

[![Build Status](https://travis-ci.org/RodrigoPrior/icelera_eeg_binary_parser.svg?branch=master)](https://travis-ci.org/RodrigoPrior/icelera_eeg_binary_parser)

Parse iCelera binary eeg output file to csv (work in progress).

### Initiative

As long as iCelera does not provide any documentation about its binary output
file we decide to reverse engineer it.

### Why?

To use the output in various statistical methods and visualization platforms.

### Requirements

- Python +2.7.x or Python +3.4.x
 - Numpy  
 - Pandas  
 - Struct  

### Fast Track

    $ git clone <this project>
    $ pip install -r requirements.txt
    $ python iceleracli.py -f example/example.dat
    $ <text editor> example/example.dat.csv

### References

I used some external references to decode and convert. The binary output file have some similarities to other eeg providers.

ftp://ftp.egi.com/pub/documentation/manuals/Net_Station_4.5/ff_093004.pdf  
http://wiki.neuroelectrics.com/index.php/Files_%26_Formats  
http://sccn.ucsd.edu/eeglab/testfiles/EGI/NEWTESTING/rawformat.pdf  

### TODO

- [ ] icelera.py
  - [ ] fix input date
  - [ ] fix timeseries frequency rate
