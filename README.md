## PT ELEKTRIN Consignment Sales Information System Design

## 📌 Project Overview:
This project presents the system analysis and design of a consignment sales information system for PT ELEKTRIN, a manufacturing company that distributes electronic products through a consignment model. The system manages order processing, inventory control, consignment sales, returns (unsold and damaged goods), invoice generation, commission calculation, and monthly reporting.

## Diagrams Included:

### 1️⃣ Use Case Diagram
Illustrates system interactions between:
- Sales Department
- Warehouse Department
- Commissioner
- Production Department
- Manager
  
![Use Case Diagram](usecase.jpg)


### 2️⃣ Sequence Diagram – Retur Konsinyasi

Describes the detailed return process including:
- Commissioner submits return request
- Warehouse records return form
- System saves return data
- Alternative flow:
  - Unsold goods → Stock updated
  - Damaged goods → Sent to Production for inspection and status update

![Sequence Diagram](sequence.jpg)


### 3️⃣ Domain Model Class Diagram

Represents core system entities including:
- Customer
- Commissioner
- Product
- Warehouse
- Stock
- Sales
- Consignment Sales
- Invoice
- Return
- Damaged Goods

![Domain Model](domain.jpg)


