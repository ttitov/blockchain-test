# blockchain-test
Test and learn blockchain


Example 

~ curl -i http://localhost:5000/mine
~ curl -i http://localhost:5000/chain
~ curl -X POST -H "Content-Type: application/json" -d '{
 "nodes": ["http://127.0.0.1:5001"]
}' "http://localhost:5000/nodes/register"
