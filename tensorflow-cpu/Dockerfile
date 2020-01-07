FROM tensorflow/tensorflow:1.14.0-py3
RUN apt update
RUN apt install -y git
RUN pip install --upgrade pip
RUN pip install tensorflow-datasets
RUN git clone https://github.com/JPLeoRX/tf-cifar10.git
CMD ["python", "./tf-cifar10/cifar_run_simplified.py"]