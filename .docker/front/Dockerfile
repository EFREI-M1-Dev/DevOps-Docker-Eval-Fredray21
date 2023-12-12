FROM node AS final
WORKDIR /app

# On install git et on clone le repo vitrine_back
RUN apt-get update && apt-get install git -y
RUN git clone https://github.com/TheBigBrownBear/vitrine_front.git ./vitrine_front

# On install serve pour servir le frontend
WORKDIR /app/vitrine_front
RUN npm install -g serve

ENTRYPOINT ["serve", "-s", ".", "-l", "80"]
