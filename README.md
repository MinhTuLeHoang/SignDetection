# SignDetectionCPP


- Install Tensorflow for C++: https://www.tensorflow.org/install/lang_c


## Install Tensorflow for C++:

- Download:
```
FILENAME=libtensorflow-cpu-linux-x86_64-2.7.0.tar.gz
wget -q --no-check-certificate https://storage.googleapis.com/tensorflow/libtensorflow/${FILENAME}
sudo tar -C /usr/local -xzf ${FILENAME}
```

- Linker Config:
```
sudo ldconfig /usr/local/lib
```


