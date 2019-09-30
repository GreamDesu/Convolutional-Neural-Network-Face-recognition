# Computer Vision: Face Recognition
An python application that can recognize the faces of our classmates and give a small physical description:

## File description:
  - **face-recognition.ipynb** - main file with code for recognizing people's faces and training on a dataset
  - **master-file.ipynb** - lite version of the file with code for recognizing people's faces, without training
  - **api-tester.ipynb** - file for tests of various APIs from the list
  - **/models** - a model for the dlib library that recognizes the position of face elements
  - **/weights** - pre-trained model taken from http://vintage.winklerbros.net/facescrub.html, trained for more than 100,000 pictures of 530 people.
  - **/images** - storage of photos of all people from the dataset
  - **align.py**, **model.py**, **utils.py** - some libs
  - **finalized_model.sav** - a manually trained face model supplemented by student faces. Based on the dataset from the folder **/weights**
  - **finalized_encoder.sav** - saved encoder of our images
  
## How to install:
  * 0a. In case you do not have a webcam on your Pc:
    Install Epoccam software on your smartphone and connect to PC
  * 0b. In case you do have webcam, programm will use it instead
  
  1. Install Python 3
  2. Install Jupiter Notebook from jupyter.org
  3. In terminal run:
  ```
  pip install cmake
  pip install dlib
  pip install Keras
  pip install -r requirements.txt
  ```

## How to run:
  1. Start Jupyter, it will automatically open in brower
  2. Upload your dataset with person photos to ../images/%person-name%/ for all people you have
  2. In Jupyter open face-recognition.ipynb file
  3. Then restart Kernel by: Kernel -> Restart Kernel and Run All Cells
  4. Enjoy!

