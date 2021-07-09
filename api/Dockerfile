FROM python:3.9.5
RUN pip install flask
RUN pip install Flask-Cors
COPY . .
ENV FLASK_ENV=development
ENV FLASK_APP=app.py
EXPOSE 5000
CMD ["flask", "run", "--host", "0.0.0.0"]