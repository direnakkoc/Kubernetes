FROM node

COPY *.js /app/
COPY products.json /app/
COPY package*.json /app/

WORKDIR /app/
RUN npm ci

CMD ["node", "index.js"]