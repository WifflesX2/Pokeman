# Pokeman
Some of you dummies can't tell the difference between real and fake pokemon cards. So I made an AI that does it for you. 

In order for the best results keep the pokemon card with the blue back-cover with the pokeball facing the camera and facing portrait(hotdog). Preferable take photo with a white backround (one a blank piece of printer paper will do)

## The Algorithm

This algorithm uses ImageNet to distinguish two classes "real" and "fake" it scans you imaghe and compares it to the dataset it has. The dataset has over 400 images so the algorithm is prettty well trained at recognizing counterfeits. I you really want to learn all the logistics of how it works, look it up on the internet. 

## Running this project

1. You need to download an image and use this code here:
python3 my-recognition.py example.jpg
2. place the image inside the pokemon-cards folder in order to do this you may need to make a new file but just ctrl+C into the folder will work. 
3. Required libraries are jetson-inference and python-3

For people who can't read: (video link)
https://youtu.be/WelsScs0AVw
