# hash:sha256:3a2e18a3cdae795a40d14ad2aacc3bbb889085254ffa2bf08ebf126aa21c2893
FROM registry.codeocean.allenneuraldynamics.org/codeocean/jupyterlab:3.0.9-miniconda4.9.2-python3.8-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

ARG GIT_ASKPASS
ARG GIT_ACCESS_TOKEN
COPY git-askpass /

RUN pip install -U --no-cache-dir \
    h5py==3.8.0 \
    matplotlib==3.7.0 \
    natsort==8.2.0 \
    numpy==1.24.2 \
    opencv-python==4.7.0.68 \
    pandas==1.5.3 \
    scikit-image==0.19.3 \
    scipy==1.10.0 \
    toml==0.10.2
