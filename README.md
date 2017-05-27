# video_to_sequence
* TensorFlow Implementation of [Sequence to Sequence – Video to Text](http://arxiv.org/abs/1505.00487)

### Usage
* Install caffe and tensorflow
 * Download Microsoft Video Description Corpus and the corresponding video data
 * Download both data from http://www.cs.utexas.edu/users/ml/clamp/videoDescription/
* Preprocess downloaded videos
 * Download VGG_ILSVRC_19 model from https://worksheets.codalab.org/bundles/0x54101cad2a56410c843b14153371aa5c/
 * Set paths in cnn_utils.py and preprocess.py according to your environment
* Sample & extract features by running "preprocessing.py"
 * Train: train() in model.py
 * Set paths in model.py according to your environment
 * Test: test() in model.py
 * Evaluation: use code found at https://github.com/vsubhashini/caption-eval with the output created by model.test() (my.txt, ref.txt)

### License
* BSD License
