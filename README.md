# Pool Drowning Detection using Deepstream 5.0 on Jetson Nano with YOLO v4 tiny model

* Model compined from yolo to tensorrt compatible version
* Pipeline created for inference with the following components

>    pipeline.add(source)   
>    pipeline.add(h264parser)    
>    pipeline.add(decoder)

>    pipeline.add(streammux

>    pipeline.add(pgie)

>    pipeline.add(nvvidconv)

>    pipeline.add(nvosd)

>    pipeline.add(sink)

* Output added to a sink  (the monitor/display) in this case

# To run 
* Clone the directory 
* Copy the test_1.h264 file into the same directory
* Run the command `python3 detect_pipeline.py test_1.h264`
