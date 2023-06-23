FROM python:3.10

WORKDIR /app

RUN pip install --no-cache-dir jupyter pandas numpy matplotlib scikit-learn cassandra-driver seaborn

RUN mkdir data

COPY data/*.csv /app/data/

CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--port=8888", "--no-browser", "--allow-root", "--NotebookApp.token=''", "--NotebookApp.password=''"]