docker build -t amoshydra/puppeteer:1.17.0-dubnium .

docker tag amoshydra/puppeteer:1.17.0-dubnium amoshydra/puppeteer:1.17.0-dubnium
docker push amoshydra/puppeteer:1.17.0-dubnium

docker tag amoshydra/puppeteer:1.17.0-dubnium amoshydra/puppeteer:latest
docker push amoshydra/puppeteer:latest
