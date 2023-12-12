# Backend Dockerfile
FROM node AS final
WORKDIR /app

# On install git et on clone le repo vitrine_back
RUN apt-get update && apt-get install git -y
RUN git clone https://github.com/TheBigBrownBear/vitrine_back.git ./vitrine_back

# On install les dépendances du backend
WORKDIR /app/vitrine_back
RUN npm install

ENTRYPOINT ["node", "server.js"]
