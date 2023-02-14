# hash:sha256:c14f3aaa00cae4fadf36cf6870696e6294efc399bd16cfe7bc8f580f4b295ba9
FROM registry.codeocean.allenneuraldynamics.org/codeocean/jupyterlab:3.0.9-miniconda4.9.2-python3.8-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

ARG GIT_ASKPASS
ARG GIT_ACCESS_TOKEN
COPY git-askpass /

RUN pip install -U --no-cache-dir \
    cv2 \
    glob \
    h5py \
    matplotlib \
    natsort \
    numpy \
    os \
    pandas \
    pil \
    scipy \
    skimage \
    streamlit
