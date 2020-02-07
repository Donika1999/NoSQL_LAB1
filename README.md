# NoSQL_LAB1

This lab is based on **Map Reduce programs on Hadoop**.

1. Setup a single node cluster Hadoop.

2. Input file consists of the NCDC weather data and the Map Reduce program returns yearly the Maximum Temperature recorded. </br>
NCDC data: </br>
1901: https://github.com/tomwhite/hadoop-book/blob/master/input/ncdc/all/1901.gz </br>
1902: https://github.com/tomwhite/hadoop-book/blob/master/input/ncdc/all/1902.gz

3. Input file consists of web access log produced by a web server and the Map Reduce program called "ImageCounter" counts the number of times GIF, JPG, and other image files that have been accessed by clients. The MR Job output contains three figures: number of GIF requests, number of JPEG requests, and number of other images.

4. With the same input file as above, the Map Reduce program outputs the total number of requests and the total download size (in mega bytes) on monthly basis. The output contains <Year-Month, Number of Requests, Download Size> for every month like Dec-2016, Jan-2017, and so on.

5. With the same input file as above, the Map Reduce program lists Timestamp, URL for which http response status has been **404**. This is done using map only MR job.

**References** : </br>
https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-common/SingleCluster.html</br>
https://github.com/tomwhite/hadoop-book/tree/master/ch02-mr-intro/src/main/java </br>
https://data-flair.training/blogs/map-only-job-in-hadoop-mapreduce/ </br>
https://httpd.apache.org/docs/1.3/logs.html#common </br>

Note: </br>
The lab content has been given by prof. PM Jat.
