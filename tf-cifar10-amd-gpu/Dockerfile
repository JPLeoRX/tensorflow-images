FROM rocm/tensorflow:rocm2.9-ub18.04-tf1.15-python3
RUN apt update
RUN pip install --upgrade pip
RUN pip install tensorflow-rocm==1.14.0
RUN pip install tensorflow-datasets
RUN git clone https://github.com/JPLeoRX/tf-cifar10.git
CMD ["python3", "./tf-cifar10/cifar_run.py"]