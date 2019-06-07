FROM anthonysigogne/web-search-engine


COPY ./run_worker.py ./
COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

CMD [ "python", "run_worker.py" ]
