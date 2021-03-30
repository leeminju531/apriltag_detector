# AprilTag-Detector-Ros
AprilTag_ros detector node on ROS 

# file Description 

1. config/Available_tag.yaml
 
  BaseFrame : please write your robot base frame
              default - base_footprint
              
  Tag : write tag frame name you want detect
              
  WorkerThread : worker threads check tf buffer whether tag frame exist or not
                 basically, more describe tag you wanna detect ,increase worker thread number
                 
                default : 4
execute main node after load yaml.     

2.  main node publish detected Tag's (you have to describe yaml 'Tag')
