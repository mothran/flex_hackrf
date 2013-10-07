#FLEX_hackrf

flex_hackrf is an attempt to make a functional flex decoder / scanner using the hackrf as a souce.  It is heavely based on the examples that come with gr-pager and I would like to thank Johnathan Corgan for his work on creating this addon to gnuradio



##Usage

Make sure your hackrf is function and open to be read from:
	hackrf_info


Now run flex.py
	python flex.py -f FREQENCY

Example:
	python flex.py -f 931.95M
