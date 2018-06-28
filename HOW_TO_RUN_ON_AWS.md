#How to run the project on AWS

1. Launch instance from the AWS Deep Learning AMI, tested on (Ubuntu) Version 10.0 (ami-958d8bec in eu-west-1) 
2. Select a GPU instance type such as p2.xlarge, remaining launch wizard preferences can remain unchanged
3. ssh into the machine
4. run "source activate cntk_p36" 
5. run "git clone https://github.com/sswarnakar/LifeGuard.IO.git"
6. run "pip install pillow imageio"
7. run "conda install ffmpeg -c conda-forge"
8. go to folder Implementation and run "python Conv3D_UCF11.py" 
