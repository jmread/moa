Multi-label branch of MOA
=========================

Multi-label classification should work out-of-the-box in MOA. If you want to run some examples:

1. Either
	* Checkout the code from this repository (`multilabel` branch); or 
    * Checkout the code from the main repository and download the following files:
		- `meka-1.9.1-SNAPSHOT.jar` (or compile it yourself from the [Meka](https://github.com/Waikato/meka) project
		- `test.sh` contains many examples
		- `align.sh` simply an auxilliary script for aligning output neatly on the terminal
2. Check the `CLASSPATH` options in the beginning of `tesh.sh`
3. Download a dataset, for example `A-TMC7-REDU-X2-500.arff` is the default one used in the script
4. Run the script, e.g., `./test.sh 0` if you want to test the code from the [2012 paper](http://www.springerlink.com/content/5q7gg153j4327h23/). 

For more (older) information, see this [link referenced in the paper](http://meka.sourceforge.net/ml.html)
