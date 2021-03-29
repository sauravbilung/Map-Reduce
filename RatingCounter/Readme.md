Datasets : https://grouplens.org/datasets/movielens/ <br>
Download : https://files.grouplens.org/datasets/movielens/ml-100k.zip <br>
Dataset to use : u.data <br>
Headings in u.data : userid,itemsid/movieid,rating(1-5),timestamp <br>

To execute type in spyder console: <br>
!python RatingCounter.py path-to-data/ml-100k/u.dat <br>

Note: Different versions of mrjob use different parameters and the name of those parameters change, so install <br>
appropriate versions of mrjob(map reduce job) packaage in anaconda.
