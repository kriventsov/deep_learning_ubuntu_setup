# Setting up a deep learning environment with Python 3.6, Keras, Tensorflow and OpenCV for Ubuntu 16.04 on a Google Cloud VM instance

This repository contains step-by-step instructions for creating a deep learning machine under Ubuntu 16.04. In my case I created it on a Google Cloud VM instance, so I included the instructions for settting up such instance in Step 1. If you are using a local machine or a different cloud (e.g. AWS), I suppose you should still be able to use steps 2 - 10 for your setup, although I have not performed any testing to verify this.

The total time you should expect to spend on this installation is 2.5 - 3 hours. Most of this time will be spent on building and installing OpenCV, which is only necessary for working with images. If you don't need OpenCV, please skip steps 3, 5, and 7-9. 

As of April 17, 2018, I have verified that these instructions work when followed exactly. The behavior of some download links and other features may change in the future. I will update this tutorial in case if I become aware of any issues. However, I am not planning to test it regularly to confirm that everything is still up-to-date.

When creating these instructions, for certain parts I used several excellent tutorials available online which are cited within the file.

Of course, if you choose to follow these instructions, you are doing it at your own risk. I provide no guarantees and will assume no liability for any results you might have.
