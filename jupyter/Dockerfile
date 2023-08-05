FROM python:3.7-slim

RUN mkdir src
WORKDIR /src
COPY . /src
RUN pip install jupyter
CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--port=8888", "--allow-root", "--no-browser"]