# masktracker
Jetson Nano Demo Project


# usage
1. download the project and place it into the specificed model directory under jetson-inference
2. open command line tool
3. cd to jetson-inference directory
4. start docker by running "docker/run.sh"
5. cd to the project directory
6. detectnet --model=models/masktracker/ssd-mobilenet.onnx --labels=models/masktracker/labels.txt --input-blob=input_0 --output-cvg=scores --output-bbox=boxes /dev/video0"
