# Blockchain
Test and learn Blockchain


**Example:**

~ curl -i http://localhost:5000/mine

~ curl -i http://localhost:5000/chain

~ curl -X POST -H "Content-Type: application/json" -d '{
 "nodes": ["http://127.0.0.1:5001"]
}' "http://localhost:5000/nodes/register"


from:

https://habrahabr.ru/company/everydaytools/blog/339280/

original:

https://hackernoon.com/learn-blockchains-by-building-one-117428612f46