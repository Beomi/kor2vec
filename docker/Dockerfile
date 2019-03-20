FROM pytorch/pytorch:0.4.1-cuda9-cudnn7-runtime

WORKDIR /workspace

ENV LANG C.UTF-8
ENV LC_ALL C.UTF-8

RUN git clone https://github.com/naver/kor2vec .

RUN pip install .

