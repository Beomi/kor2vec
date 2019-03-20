FROM pytorch/pytorch:0.4.1-cuda9-cudnn7-runtime

WORKDIR /workspace

RUN git clone https://github.com/naver/kor2vec .

RUN pip install .

ENTRYPOINT kor2vec
