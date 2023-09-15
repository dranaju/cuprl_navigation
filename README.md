# CUPRL Implementation

On this code you can run CUPRL, Depth-CURPL, classic CURL and SAC-CNN with prioritized memory:

roslaunch hydrone_aerial_underwater_ddpg hydrone_aerial_deep_rl.launch world_name:=stage_2_aerial gui:=false

roslaunch curl_navigation 2_curl.launch

tensorboard --logdir=evaluations
