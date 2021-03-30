# AprilTag-Detector-Ros
AprilTag_ros detector node on ROS 
![ezgif com-gif-maker (10)](https://user-images.githubusercontent.com/70446214/113014816-e4498c00-91b7-11eb-8936-0548b1e1bd2a.gif)

# file Description 

1. config/Available_tag.yaml
 
  BaseFrame : please write your robot base frame  
              __default - base_footprint__
              
  Tag : write tag frame name you want detect  
              
  WorkerThread : worker threads check tf buffer whether tag frame exist or not
                 basically, more describe tag you wanna detect ,increase worker thread number  
             __default : 4__  
execute main node after load yaml.     

2.  main node publish detected Tags (you have to describe yaml 'Tag')
