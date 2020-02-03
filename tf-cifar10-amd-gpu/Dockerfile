FROM rocm/tensorflow:rocm3.0-tf1.14-python3
RUN apt update
RUN apt install -y git
RUN pip install --upgrade pip
RUN pip install tensorflow-datasets
RUN git clone https://github.com/JPLeoRX/tf-cifar10.git
CMD ["python", "./tf-cifar10/cifar_run.py"]