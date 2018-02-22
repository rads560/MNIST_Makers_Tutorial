Environment Setup...
	1. Go to https://www.anaconda.com/download and download the
		Python 3.6 version for your system
	2. Open the terminal and run conda info to ensure this was done
	3. Run conda create - makers python=3.5
	4. On windows, run activate makers OR on unix systems, source
		activate makers
	5. Make sure pip is installed with pip -v
		- If it's not, go to https://pip.pypa.io/en/stable/installing/ and install it
	6. On windows, run pip install --ignore-installed --upgrade tensorflow OR on unix systems, pip install tensorflow
	7. Check that this worked by typing python and then import tensorflow as tf
	8. Run conda install scikit-learn
	9. Check that this worked by typing python then import sklearn
	10. Check numpy with python then import numpy as np
	11. Run python -mpip install -U pip
	12. Run python -mpip install -U matplotlib
	13. Run pip install keras
	14. Run pip install keras-tqdm
	15. Run jupyter nbextension enable --py --sys-prefix widgetsnbextension
	16. Launch notebook with jupyter notebook