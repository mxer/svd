# svd
Audio segmentation using energy


INTRODUCTION
SVD i.e. Singular Valuse Decomposition is applied on pooled time-frequency representation of bird vocalizations to learn basis vectors.By ustilizing only few of the bases,a compact feature representation is obtained for the test data.
After some simple post-processing, a threshold is used to reliably distinguish bird vocalizations from other sounds.


ABOUT CODE
Code works perfectly with  Python 2 (2.7+, possibly also 2.6).
You can run the included svd.py script in the following format:

python svd.py testFilePath segmentedAudiosDirectoryPath

Number of raining files are mentioned using numTrainFiles variable which can be modified accordingly.
Path of training data is mentioned using trainPath1,trainPath2,trainPath3 variables,which can be commented out depending on number of training files.

The code internally performs checks to see if path to code,test file and segmentation directory is mentioned properly.

