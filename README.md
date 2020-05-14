# logo-detection
This app alows the users to simply select a photo from their photo library and upload it to fund out what brand logos are presented
in the image 

Selecting an Image
For selecting the image and getting access to the photo library the project uses 'react-native-image-picker' library.
The project follows the guide from 'https://heartbeat.fritz.ai/how-to-upload-images-in-a-react-native-app-4cca03ded855' to achieve this.

Logo detection
For detecting the logos presen in an image the project uses Google Cloud Vision API logo detection tool.
You can find more inoformation here: 'https://cloud.google.com/vision/docs/detecting-logos#vision_logo_detection-nodejs'
