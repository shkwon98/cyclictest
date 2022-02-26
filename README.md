# Cyclictest
Real-time benchmark for RTOS

#
### INSTALL:

    ~ $ sudo apt-get install -y build-essential git
    ~ $ git clone git://git.kernel.org/pub/scm/utils/rt-tests/rt-tests.git
    ~ $ cd rt-tests
    ~/rt-tests $ git checkout stable/v1.0
    ~/rt-tests $ make cyclictest
    ~/rt-tests $ sudo make install
    
### RUN:

    sudo cyclictest –l500000 –m –n –S –p90 –i200 –h400
    
### PLOTTING:
    
    ~ $ sudo apt-get install gnuplot-x11
    ~ $ mkdir mklatencyplot
    ~ $ cd mklatencyplot
    ~/mklatencyplot $ wget https://raw.githubusercontent.com/shkwon98/RPi_Latency_test/main/mklatencyplot.bash
    ~/mklatencyplot $ sudo bash mklatencyplot.bash
