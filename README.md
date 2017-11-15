# ksql_memo
This is Memo repository for KSQL

## What is KSQL

KSQL is one of Kafka client. A Client can use as SQL client. 

## Technique
 
* stream table should have only valid data

if your topic contains not only valid data but also invalid data as error data, then ksql terminates stream getting. 
