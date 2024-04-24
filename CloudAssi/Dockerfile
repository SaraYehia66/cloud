FROM python
WORKDIR /app
COPY assignment.py /app
COPY paragraphs.txt /app
RUN pip install nltk
RUN python -m  nltk.downloader stopwords punkt
CMD ["python", "assignment.py"]
