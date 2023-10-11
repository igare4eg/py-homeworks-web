FROM python:3.10


COPY ./crud/stocks_products /crud/stocks_products
WORKDIR /crud/stocks_products

RUN pip install --no-cache-dir --upgrade -r /crud/stocks_products/requirements.txt

EXPOSE 3773

CMD ["python3", "manage.py", "runserver", "0.0.0.0:3773"]