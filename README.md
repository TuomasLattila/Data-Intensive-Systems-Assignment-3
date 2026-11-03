# Data-Intensive Systems database schema modeling assignment

PlantUML and draw.io were used to generate the diagrams.

## Database entities
- CUSTOMERS(CID, NAME, ADDRESS (STREET, CITY, STATE, COUNTRY), PHONES)
- ORDERS(OID, CID, O-DATE, O-TOTAL)
- ORDER-ITEMS(OID, LINE-ID, PID, QTY)
- PRODUCTS(PID, P-NAME, PRICE)

## ER Model
![ER model](images/ER-diagram.png)

## Graph database schema
![Graph model](images/Graph-schema.png)

## Wide-column schema
![Wide-column model](images/wide-column_schema.png)

## JSON data representation
![JSON data representation](images/JSON-representation.png)