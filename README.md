# Landmark-Image-Recognition
Implement a 2D-CNN model to recognize landmarks using images. 
The goal is to classify landmark images into one of the 10 categories below.

0. St. Stephan's Cathedral, Austria 
1. Teide, Spain 
2. Tallinn, Estonia 
3. Brugge, Belgium 
4. Montreal, Canada 
5. Itsukushima Shrine, Japan 
6. Shanghai, China 
7. Brisbane, Australia 
8. Edinburgh, Scotland 
9. Stockholm, Sweden

The dataset is subset of the Google Landmark Recognition Challenge.

## File descriptions:
• train.csv - The training file which contains columns id, url and landmark_id. You will use the columns id and landmark_id primarily. The id column will be used to map to the image in the images folder. e.g. 192333daaf6119cf will map to 192333daaf6119cf.jpg which belongs to location_id 3. The landmark_id column provides groundtruth labels for the train set. Ignore the url column.
• test.csv - The test file for which you will be making predictions. It contains columns id, url and landmark_id. Ignore the url column. As with the training data, you will use the id values to map to image in the images folder, and the landmark_id column for groundtruth labels on the test set.
• images.zip - An archive containing all images, test and train.

## Data fields
• id - an anonymous id unique to a given image in the images folder
• landmark_id - the id of a landmark
