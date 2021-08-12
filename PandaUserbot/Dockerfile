FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ilhammansiz/PandaWaUserbot /root/PandaWaUserbot
WORKDIR /root/PandaWaUserbot/
ENV TZ=Asia/Jakarta
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "Panda/main.js"]
