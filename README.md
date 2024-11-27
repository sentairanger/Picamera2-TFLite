# Picamera2-TFLite
This project uses TFLite and PiCamera2 for image classification. 

## Getting started

This application works best on Raspberry Pi OS Bookworm 64-bit. This can work on any Pi that supports 64 bit. This includes the Pi 3, 3B+, 3A+, 4, 5, CM3, CM3+, CM4, CM4S, CM5 and Pi Zero W 2. Any camera module should work just fine. The `requirements.txt` file is needed to install numpy and pillow. Also you should run this application using a Virtual environment. For example, you can create an environment called `venv` by running `python3 -m venv`. However it's best to use the system wide packages so run `python3 -m venv --system-site-packages`. Then activate with `source venv/bin/activate`. After that you can run `pip install -r requirements.txt` to install pillow and numpy. Then install tflite with `pip install tflite-runtime`. Run the application with `python3 app.py` and it should look just like the screenshot below. Press the buttons to capture and classify any image. 

![image](https://github.com/sentairanger/Picamera2-TFLite/blob/main/20241127_16h23m58s_grim.png)
