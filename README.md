# Sign Language Detection

This project is for detection of only five sign "Hello", "Yes", "No", "Thank You" and "I Love You"

## Files

- create folder darknet--->clone github repo of darknet 
- create folder labelImg--->clone labelImg repo for labelling image
- create folder custom_weight--->Download pre-trained weights for the convolutional layers (154 MB)
- two .py files is for creating labeled, train, and test data.
- re-write the MakeFile in darknet folder
- paste "yolov3_custom.cfg" in cfg folder in darknet folder
- create backup folder

## Install
- for labelImg
```bash
git clone https://github.com/tzutalin/labelImg.git
```
- for darknet
```bash
git clone https://github.com/AlexeyAB/darknet.git
```
- for pre-trained weights for the convolutional layers
https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbmZodkpzNHQyQWQyeFRoeWlHTWVDZGZOZXRkZ3xBQ3Jtc0tuVGNmeEt0RkFCSThmRDdTYi04QmlkU043NFMxYnh5Q1FRQlZObnpxaEFSb2JRanlYaDlmanVFdVNwQ2tibllZR3hfQlZYYS1maEZMazFBYkRhN1FPbjhJR1ZfOTQyaVNldE9yZXFiLWFQWHF5V2xsSQ&q=http%3A%2F%2Fpjreddie.com%2Fmedia%2Ffiles%2Fdarknet53.conv.74

## Status of the Project
It is not complete as i ws unable to train model and a file name "bad-label.list" was made. 
