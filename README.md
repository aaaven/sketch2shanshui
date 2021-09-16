This is sketch2shanshui dataset created by [Aven Le Zhou](https://www.aven.cc) for shanshuiDaDA project.

## Basic Info
* sketch2shanshui
  * dataset dimension: 1771 pairs of 512\*512\*3 images

  * raw image sources (205 paintings)
    * (112 paintings) [the National Palace Museum Open Data Platform](https://theme.npm.edu.tw/opendata/?lang=2)
    * (93 paintings) and [Chinese online shopping platform](https://www.taobao.com/)

* sketch2shanshui file structure
  * NPM
    * ~~raw~~
    * ~~frame_removed~~
    * 512\*512
  * TAOBAO
    * raw
    * frame_removed
    * 512\*512
  * sketch2shanshui
    * trainA
    * trainB

## Citation
This dataset and related work are explained in details and published in a paper titled "An Interactive and Generative Approach for Chinese Shanshui Painting Document", please check the details below for citation:

"""
@INPROCEEDINGS{8978182,
  author={Zhou, Le and Wang, Qiu-Feng and Huang, Kaizhu and Lo, Cheng-Hung},
  booktitle={2019 International Conference on Document Analysis and Recognition (ICDAR)}, 
  title={An Interactive and Generative Approach for Chinese Shanshui Painting Document}, 
  year={2019},
  volume={},
  number={},
  pages={819-824},
  doi={10.1109/ICDAR.2019.00136}}
  """
