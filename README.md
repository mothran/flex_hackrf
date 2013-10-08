#FLEX_hackrf

flex_hackrf is an attempt to make a functional flex decoder / scanner using the hackrf as a source.  It is heavenly based on the examples that come with gr-pager and I would like to thank Johnathan Corgan for his work on creating this addon to gnuradio


##Usage

Make sure your hackrf is function and open to be read from:
	hackrf_info


Now run flex.py

	python flex.py -f FREQENCY

	
Example:

	python flex.py -f 931.95M

If you do not see any "Using Volk machine" output then it did not detect and signals within the predifined range.  You might need to run

	killall python

to kill the program if that happens.  Currently flex_hackrf only scans between 929 Mhz and 932 Mhz.