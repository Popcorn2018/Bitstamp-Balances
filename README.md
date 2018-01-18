# Bitstamp-Balances

Upload this to your webserver then:
  cd /root/node-crypto-api-kwiksand
  forever start app.js

Then you can use the following code in a google sheet script to get your bitstamp balances:
var response = UrlFetchApp.fetch("http://You.rIP.Add.res:3233/cryptobalance/bitstamp?CUSTOMER_ID="+custNo+"&API_KEY="+key+"&API_SECRET="+secret);

