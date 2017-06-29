# object-detection

### About
Machine learning and OpenCV for object (car) detection in video.

### Data

* [GTI vehicle image database](http://www.gti.ssr.upm.es/data/Vehicle_database.html)
* [KITTI vision benchmark suite](http://www.cvlibs.net/datasets/kitti/)
* Images extracted from project videos

Links to labeled data (compiled / provided by udacity):

* [vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/vehicles.zip) 
* [non-vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/non-vehicles.zip)


### Code
`code.ipynb` (Jupyter notebook)

* Linear SVM for image classification
* Feature vector comprises HOG, spatial binning and color histograms
* Sliding window detection combined with heatmap based elimination of false positives

### Testing

* Use `test.mp4` to test. Sample output in `out.mp4`

