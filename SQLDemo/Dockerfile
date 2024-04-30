FROM python

WORKDIR /myapp

COPY ./sql_demo.py .

RUN pip install mysql-connector

RUN pip install pymysql

CMD [ "python" , "sql_demo.py" ]

