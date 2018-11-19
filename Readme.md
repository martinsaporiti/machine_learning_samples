# Pruebas de Conceptos sobre Machine Learning

## Instalaciones necesarias

1. Python 3
2. OpenCV
   
   ```
   brew install opencv

   # Activar el virtualenv si es lo que usamos y luego ejecutar
   pip install numpy scipy scikit-image matplotlib scikit-learn

   # Parados en el path ${pwd}/cvtest/lib/python3.6/site-packages/ del virtual enviroment, vamos a crear un link a la instalación del opencv.

   ln -S /usr/local/Cellar/opencv/3.4.3/lib/python3.7/site-packages/cv2.cpython-37m-darwin.so cv2.so
   ```
3. [Dlib](https://gist.github.com/ageitgey/629d75c1baac34dfa5ca2a1928a7aeaf)
4. [Face Recognition](https://github.com/ageitgey/face_recognition#installing-on-mac-or-linux)