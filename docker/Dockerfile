FROM jupyter-tensorboard:latest

COPY . /opt/jupyterlab-tensorboard
RUN cd /opt/jupyterlab-tensorboard \
    && python3 -m pip install . \
    && fix-permissions $CONDA_DIR \
    && fix-permissions /home/$NB_USER
