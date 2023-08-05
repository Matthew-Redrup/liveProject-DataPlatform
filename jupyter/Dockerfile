FROM python:3.7-slim

RUN mkdir src
WORKDIR /src
COPY HelloWorld.ipynb /src
COPY requirements.txt /src
RUN pip install -r requirements.txt

CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--port=8888", "--allow-root", "--no-browser"]