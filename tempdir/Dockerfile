FROM python
RUN pip install flask
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  midterm_app.py /home/myapp/
EXPOSE 5000
CMD python3 /home/myapp/midterm_app.py
