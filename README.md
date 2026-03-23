Data: split into train, val, and test
  OCRcrops = image crops from object detection model + annotation sets (annotatedTest.csv = ground truth)
  RawImages = original images

Data_preparation:
  data_prep = create a csv with crop image file and traditional ocr output at 50% confidence
  labelStudio = create json for using label studio

models:
  customyolo26n = custom tuned object detection model
