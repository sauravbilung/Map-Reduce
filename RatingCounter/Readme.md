Datasets : https://grouplens.org/datasets/movielens/
Download : https://files.grouplens.org/datasets/movielens/ml-100k.zip
Dataset to use : u.data
Headings in u.data : userid,itemsid/movieid,rating(1-5),timestamp

To execute type in spyder console:
!python RatingCounter.py path-to-data/ml-100k/u.dat

Note: Different versions of mrjob use different parameters and the name of those parameters change, so install 
appropriate versions of mrjob(map reduce job) packaage in anaconda.