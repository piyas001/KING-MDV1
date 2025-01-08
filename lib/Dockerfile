FROM quay.io/naveeddogar/kingmd
RUN git clone https://github.com/naveedbro/KING-MDV1 /root/naveedbro
WORKDIR /root/naveedbro/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
