# Computer Vision: Face Recognition
An python application that can recognize the faces of our classmates and give a small physical description:

## File description:
  - **face-recognition.ipynb** - основной фаил с кодом по распознаванию лиц людей и обучением на датасете
  - **master-file.ipynb** -облегченная версия файлаа с кодом по распознаванию лиц людей, без обучения
  - **api-tester.ipynb** - фаил для тестов различных API из Top Tens списка
  - **/data** - хранилище данных (samples, data_sets)
  - **/models** - модель для библиотеки dlib, которая распознает положение элементов лица
  - **/weights** - предобученная модель взятая из http://vintage.winklerbros.net/facescrub.html, обученная на более 100.000 лиц 530 людей.
  - **/images** - хранилище фотографий всех студентов из датасета
  - **/images** - хранилище фотографий всех студентов из датасета
  - **align.py**, **model.py**, **utils.py** - библиотеки, необходимые для правильной работы программы
  - **finalized_model.sav** - дообученная нами вручную модель лиц, дополненная лицами студентов. За основу взят датасет из папки **/weights**
  - **finalized_encoder.sav** - сохраненный encoder наших изображений
  
## How to install:
  * 0a. Если на ноутбуке нет веб-камеры:
    Установите приложение Epoccam на свой телефон и подключите его к компьютеру
  * 0b. Если вебкамера есть, то программа будет использовать её.
  
  1. Установите Python 3
  2. Установите Jupiter Notebook с сайта jupyter.org
  3. В терминале запустите:
  ```
  pip install cmake
  pip install dlib
  pip install Keras
  pip install -r requirements.txt
  ```

## How to run:
  1. Запустите Jupyter, он автоматически откроется в браузере
  2. Откройте в нем фаил master-file.ipynb
  3. В верхнем меню выбирите Kernel -> Restart Kernel and Run All Cells
  4. Enjoy!

