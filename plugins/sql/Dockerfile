FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Aj-fx/Kaztro_ser /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Aj-fx/kaztroser

CMD ["node", "bot.js"]
