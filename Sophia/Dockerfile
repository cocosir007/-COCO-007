FROM fusuf/whatsasena:latest

RUN git clone https://github.com/cocosir007/-COCO-007 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN git clone https://github.com/Hisham-Muhammed/uploads
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit


CMD ["node", "bot.js"]
