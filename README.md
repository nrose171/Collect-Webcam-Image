# Collect-Webcam-Image
This program utilizes openCV to obtain a single frame from a webcam and save it.

# Required Components
Need to have openCV installed and g++ version 5.4 or greater.

# To Compile
g++ basicImage.cpp -o \<executable filename\> \`pkg-config --cflags --libs\`
//Replace <executable filename> with whatever you want to name your executable//
EX) g++ basicImage.cpp -o img \`pkg-config --cflags --libs\`

# To Run
./\<executable filename\>
EX) ./img

# Function
Program is used to obtain an image using your webcam and save it in a jpg file.

#
Thank you,
#
Nathaniel Rose
