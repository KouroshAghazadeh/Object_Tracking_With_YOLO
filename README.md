# Object_Tracking_With_YOLO

in this Project, i use deep learning model YOLOV8 for tracking specific object. for default this model can track multiple object on same time.
for choosing specfic object you can change this code:

annotated_frame = results[0].plot()
        for result in results:
            if result.boxes.id != None:
                if result.boxes.id[0] == 1.:
                    midpoint = result.boxes.xywh[0][0:4]

you can change index of result for tracking your specific object.
