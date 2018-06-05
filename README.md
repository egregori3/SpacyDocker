FROM python:3

COPY . . 

RUN pip install spacy
RUN python -m spacy download en

