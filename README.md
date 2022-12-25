# Real-time-video-surveillance-using-raspberry-pi
IoT Raspberry Pi camera running open-cv for object detection. The camera will send an email with an image of any objects it detects. It also runs a server that provides a live video stream.

#Setup

This project uses a Raspberry Pi Camera to stream video. Before running the code, make sure to configure the raspberry pi camera on your device.

Open the terminal and run

```sudo raspi-config```

Select Interface Options, then Pi Camera and toggle on. Press Finish and exit.
You can verify that the camera works by running.

```raspistill -o image.jpg```
which will save a image from the camera in your current directory. You can open up the file inspector and view the image.
