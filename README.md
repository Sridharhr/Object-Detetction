# object-detection

### About
Machine learning and OpenCV for object (car) detection in video.

### Data
Links for labeled data used to train the classifier (data is from udacity):

* [vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/vehicles.zip) 
* [non-vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/non-vehicles.zip)

These example images come from a combination of the [GTI vehicle image database](http://www.gti.ssr.upm.es/data/Vehicle_database.html), the [KITTI vision benchmark suite](http://www.cvlibs.net/datasets/kitti/), and some examples extracted from project videos

### Code
`code.ipynb` (Jupyter notebook)

* SVM classifier for training
* Feature vector comprises HOG, spatial binning and color histograms
* Sliding window detection combined with heatmap based elimination of false positives

### Testing

* Use `test.mp4` to test. Sample output in `out.mp4`

