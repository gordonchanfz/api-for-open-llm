FROM pytorch/pytorch:latest

WORKDIR /workspace/
ENV PYTHONPATH /workspace/
COPY . /workspace/

#RUN pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple && \
RUN pip install --no-cache-dir -r /workspace/requirements.txt && \
    pip install bitsandbytes --upgrade 
