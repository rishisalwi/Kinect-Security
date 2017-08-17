# Kinect Secruity
### A motion-controlled smart home
## Hardware:
Our project incorporates the use of servo motors, an LED, an Arduino MKR1000 and a Bi-Directional Logic Level Converter. Initially the idea also included the implementation of a database to store values of various sensors (appropriate for a household) and a web app for remote management. However, due to restrictions (not being allowed to make a hotspot; networking issues), this proved infeasible.

## Software: 
To control this IoT device, a Kinect sensor was used to first capture motion data in the form of a skeletal structure in Processing.js. Then, depending on certain threshold ratios as determined by beta testers in the testing phase, unique ranges of motion were established to output certain behaviors according to certain programmed inputs. This allowed our product to be used regardless of user's height, arm length, and distance from sensor.

## How we built it: 
Kinect4Win Library
Processing
Arduino

## Challenges we ran into:
Various dysfunctional and obsolete Kinect libraries, interfacing the Kinect and Arduino hardware, and networking issues

## Accomplishments that we're proud of:
We learned to use a data visualization software for the first time, learned to implement OpenCV and came up with an innovative and creative idea for a hack. Created physical model of the hack for presentation

## What's next for Kinect Security:
IoT that can control many functions with gestures + phone app. Feedback from different sensors (e.g. temperature, humidity), with database. 

<p align="center">
  <img src ="https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/000/462/298/datas/gallery.jpg" />
