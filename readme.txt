This is a official about our casr dataset, the paper link will be added soon.
Dataset link: http://adas.cvc.uab.es/casr/

Video folder have 89 videos.
casr_annotation.pickle is the annotation of 4 cyclists.
youtube_annotation.pickle is the annotation of Youtube videos.

Here is the usage of this dataset.

mkdir data
unzip annotations.zip -d data
cd data
mkdir videos 

Then you need to download the videos and put it into the folder of videos

cd ..

You need to run 'sh extract_images.sh' for generating the images from videos. It need several hundred gigabit space. 
run the script of view.py to extact the sequeces of cyclists. For example: 'python2 view.py --dataset casr --track_number 0', see the view.py for more information.


Please cite our IEEE journal paper if you use our dataset and code.
@article{zhijie2019intention,
  title={Intention Recognition of Pedestrians and Cyclists by 2D Pose Estimation},
  author={Zhijie Fang, Antonio M. López},
  journal={IEEE Transactions on Intelligent Transportation Systems},
  year={2019}
}

You can also download from the arxiv:

@article{zhijie2019intention,
  title={Intention Recognition of Pedestrians and Cyclists by 2D Pose Estimation},
  author={Zhijie Fang, Antonio M. López},
  journal={arXiv:1910.03858},
  year={2019}
}
