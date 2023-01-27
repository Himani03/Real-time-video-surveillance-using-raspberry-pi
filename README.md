# Real-time-video-surveillance-using-raspberry-pi
IoT Raspberry Pi camera running open-cv for object detection. The camera will send an email with an image of any objects it detects. It also runs a server that provides a live video stream.

# Setup

This project uses a Raspberry Pi Camera to stream video. Before running the code, make sure to configure the raspberry pi camera on your device.

Open the terminal and run

```sudo raspi-config```

Select Interface Options, then Pi Camera and toggle on. Press Finish and exit.
You can verify that the camera works by running.

```raspistill -o image.jpg```
which will save a image from the camera in your current directory. You can open up the file inspector and view the image.

#Running the Program

Run the program

```python main.py```

You can view a live stream by visiting the ip address of your pi in a browser on the same network. 

You can find the ip address of your Raspberry Pi by typing ```ifconfig``` in the terminal and looking for the ```inet``` address.

Visit ```<raspberrypi_ip_address>:5000``` in your browser to view the stream.

# Output
![noname](https://user-images.githubusercontent.com/53009277/215036384-be101093-96e2-4a61-affd-281425a0a964.jpg)
Uper body recognition
![noname(1)](https://user-images.githubusercontent.com/53009277/215036489-12e0dc05-e2a0-4006-b5e7-6a917d2c5d1f.jpg)
Full body recognition
![noname(2)](https://user-images.githubusercontent.com/53009277/215036531-d280700c-3f72-44c3-9ee3-bb18306828c4.jpg)
Facial recognition
