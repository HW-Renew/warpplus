FROM python:3.8
LABEL maintainer="support@cosr.eu.org"

ADD . /work
WORKDIR /work

RUN pip install python-telegram-bot \
    && chmod +x warpplus.py

ENTRYPOINT ["python", "warpplus.py"]
