baselineEvaluation:

  eval.ipynb = baseline eval + class for computing accuracy and character accuracy

Data: split into train, val, and test

  OCRcrops = image crops from object detection model + annotation sets (annotatedTest.csv = ground truth)
  RawImages = original images
  tradOutput)
    annotatedTest(manually column) = ground truth
    ocrResults = baseline ocr outputs
    rawCrop = json for label studio

Data_preparation:

  data_prep = create a csv with crop image file and traditional ocr output at 50% confidence
  labelStudio = create json for using label studio

models:

  customyolo26n = custom tuned object detection model
