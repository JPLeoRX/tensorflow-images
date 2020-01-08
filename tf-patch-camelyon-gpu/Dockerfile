FROM tensorflow/tensorflow:1.14.0-gpu-py3
RUN apt update
RUN apt install -y git
RUN pip install --upgrade pip
RUN pip install tensorflow-datasets
RUN git clone https://github.com/JPLeoRX/tf-patch-camelyon.git
CMD ["python", "./tf-patch-camelyon/patch_camelyon.py"]