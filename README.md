# getcv2-rpi
Easily install opencv on raspberry pi in just 10 minutes and just 2 commands <br>
While most methods will take hours, getcv2-rpi will seamlessly install opencv and its dependencies in JUST 10 MINUTES<br>

1. Download / Clone this repository on your raspberry pi <br>
2. Run the following commands from the getcv2-rpi folder <br>
<code>sudo chmod +x mconda-dep.sh</code> <br>
<code>./mconda-dep.sh</code><br>
After this command you will have to reboot your raspberry pi <br>
<code>sudo reboot</code> <br>
After rebooting run these final commands from the getcv2-rpi folder <br>
<code>sudo chmod +x opencv.sh</code><br>
<code>./opencv.sh</code><br>
Opencv will be installed in a miniconda virtual environment called 'opencv' running python 3.4.3<br>
Activate > <code>source activate opencv</code>
Deactivate > <code>source deactivate</code><br>
NOTE: When asked where to install miniconda, input the following: <br>
<code>/home/pi/miniconda3</code><br>
