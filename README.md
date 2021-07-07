

### Title : Social Distancing & Face Mask Detector with Alarm


## The Problem It Solves
Social Distancing and wearing masks have become the 2 most popular terms in today's life to keep oneself safe from getting infected from the Novel Coronavirus. Researchers have concluded that these 2 practises are the warriors against Covid. Governments across the nation are rigorously making efforts to make these 2 practises in action. We as a team came up to a real time solution of detecting social distance between humans and detecting persons with no mask covering. This solution was needed as there is a lack of awareness among people about the major precautions which is Mask+Distance.  Neither only mask can save, nor only distancing can save you but the aggregation of these two can. <br><br>
In our project we have proposed 2 major solutions (i) Mask Covering (ii) Ensuring safe (physical/social) distance between people which is in real time.<br><br>



## Set Up

To begin with, use the requirements.txt file to install the dependencies.
```
pip install -r requirements.txt
```

## Execute

Use the following command to execute the code.
```
python social_distance_detection.py --prototxt SSD/SSD_MobileNet_prototxt.txt --model SSD/SSD_MobileNet.caffemodel --labels SSD/class_labels.txt --alarm alarm.wav
```


