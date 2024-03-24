
# SoRaSu-TCCS

A Web-based application created using HTML,CSS,JS for the frontend and Flask, SQLite, Here Routing API and SmtpJS for the backend.

SoRaSu is a Transportation Company Computerization Software (TCCS).

The TCCS is a software that can help a transport company computerize various book
keeping activities associated with its operations. The transport company receives
consignments of various sizes at (measured in cubic meters) its different offices to be
forwarded to different branch offices across the country.

Once the consignment arrives at the office of the transport company, the details of the
volume, destination address, sender address, etc. are entered into the computer. The
computer would compute the transport charge depending upon the volume of the
consignment and its destination and would issue a bill for the consignment.

Once the volume of any particular destination becomes 500 cubic meters, the
the computerization system should automatically allot the next available truck.
A truck stays with the branch office until the branch office has enough cargo to load the truck
fully.

The manager should be able to view the status of different trucks at any time. The manager
should be able to view truck usage over a given period of time.

When a truck is available and the required consignment is available for dispatch, the
computer system will print the details of the consignment number, volume, sender's name
and address, and the receiver’s name and address to be forwarded along with the truck.

The manager of the transport company can query the status of any particular consignment
and the details of volume of consignments handled to any particular destination and the
corresponding revenue generated. The manager would be able to view the availability,
waiting period and idle time of the trucks.

Product Functions:
Manager :
The manager will be responsible for the following use cases :-
1. Buying new trucks
2. Viewing Consignment Status
3. Viewing Truck Status
4. Viewing Average Waiting Time of Consignment
5. Viewing Average Truck Idle Time
6. Viewing Truck Usage
7. Viewing Branch Consignment Handling
8. Viewing live location status of the trucks

Employees :
The employees will be associated with the following use cases :-
1. Dispatching Truck
2. Validating consignment
3. Receiving Truck
4. Viewing live location of the trucks and route to destination 

Customer :
The customer will be associated with the following use cases :-
1. View truck and route details
2. Place order
3. Viewing order history
4. Viewing auto generated invoice




## Installation
- Clone this repository-Move to your workspace directory and clone this repository
```bash
git clone https://github.com/SoRaSu-SWE23/SoRaSu.git
```
- Install dependencies-
Move to the cloned repository directory and run
```bash
pip install -r requirements.txt
```

    
## Getting Started

```bash
python3 run.py
```

## Authors

- Raj Parikh
- Soukhin Nayek 
- Sukhomay Patra

