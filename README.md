# severstal-steel-defect
In this competition you will be predicting the location and type of defects found in steel manufacturing. Images are named with a unique ImageId. You must segment and classify the defects in the test set.

Each image may have no defects, a defect of a single class, or defects of multiple classes. For each image you must segment defects of each class (ClassId = [1, 2, 3, 4]).

The segment for each defect class will be encoded into a single row, even if there are several non-contiguous defect locations on an image. You can read more about the encoding standard on the Evaluation page.

Submissions to this competition must be made through Kernels. After your submission against the Public test set, your kernel will re-run automatically against the entire Public and Private (unseen) test set. Refer to the Kernels Requirement Page for more information.

Files
train_images/ - folder of training images
test_images/ - folder of test images (you are segmenting and classifying these images)
train.csv - training annotations which provide segments for defects (ClassId = [1, 2, 3, 4])
sample_submission.csv - a sample submission file in the correct format; note, each ImageId 4 rows, one for each of the 4 defect classes
