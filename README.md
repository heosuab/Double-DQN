# Double-DQN
# Requirements
~~~
pip install torch python-opencv numpy 
~~~
~~~
!pip install gym[all]==0.17.* pyvirtualdisplay==0.2.* PyOpenGL==3.1.* PyOpenGL-accelerate==3.1.*
~~~
~~~
!apt-get install -y xvfb x11-utils
~~~
### Getting ROMS
~~~
! wget http://www.atarimania.com/roms/Roms.rar && unrar x Roms.rar
~~~
~~~
! unzip ./ROMS.zip
~~~
~~~
! pip3 install gym-retro
~~~
~~~
! python -m atari_py.import_roms ./drive/MyDrive/DDQN/ROMS/
~~~
