FROM node
WORKDIR /home/eduardo/takehome-devops/services/feed
COPY . .
RUN apt-get update && apt-get install -y default-jre
RUN npm install
RUN npm install xhr2
RUN npm run release
EXPOSE 3000
CMD ["./entrypoint.sh"]
#RUN USERINFO_URL=http://localhost:8037/api/userinfo npm run start
