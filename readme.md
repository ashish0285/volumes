gigs.json in this folder is uploaded to elasticsearch using elasticdump command

elasticdump --input=./gigs.json --output=http://elastic:admin1234@localhost:9200/gigs