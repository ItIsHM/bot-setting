FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Raashii/bot-setting /root/WhatsAsenaDuplicated

WORKDIR /root/WhatsAsenaDuplicated/

RUN git clone https://github.com/ItIsHM/media-1

ENV TZ=Europe/Istanbul

RUN npm install supervisor -g

RUN yarn install --no-audit

CMD ["node", "bot.js"]
