FROM python:3
WORKDIR /home/eduardo/takehome-devops/services/auth
COPY . .
ADD src/server.py /
RUN pip install pipenv
RUN pip install aiohttp
CMD [ "python", "src/server.py" ]
