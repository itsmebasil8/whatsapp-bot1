FROM quay.io/souravkl11/raganork:multidevice

RUN git clone https://github.com/itsmebasil8/raganork-md /itsmebasil8/raganork-md
WORKDIR /itsmebasil8/raganork-md
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]
