# masktracker
Jetson Nano Demo Project


# usage
1. download the project and place it into the specificed directory under jetson-inference
2. open command line tool
3. run "cd to the project"
4. run "detectnet --model=models/masktracker/ssd-mobilenet.onnx --labels=models/masktracker/labels.txt --input-blob=input_0 --output-cvg=scores --output-bbox=boxes /dev/video0"
