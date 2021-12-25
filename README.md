# COMPUTER NETWORK CASE STUDY
## Warehouse Management System


### Problem Statement:

To design an efficient networking system for improved management of warehouses,
spread across a region. The most effective warehouse system products raise the operating
performance which leads to more productivity. It ensures smooth production operations by
maintaining reasonable stocks of materials.

# Cisco Packet tracer Implementation
## Procurement Department :
When new products arrive at the warehouse they are scanned , labelled and entered into the system .
## Shipment:
The product is checked and packed accordingly and an entry in the system is made before the product is out for shipment
## Head Office :
Where queries and data about the product are sent through mail .

Starting Address: 182.28.20.0


| Department | No of devices  |
| :---:   | :-: |
| Procurement In 1 WIRELESS | 4 |
| Procurement In 1 WIRED | 7 |
| Procurement In 1 WIRELESS | 4 |
| Procurement In 1 WIRED | 7 |
| Outlet 1 biling | 10 |
| Outlet 1 delivery | 10 |
| Outlet 2 biling | 7 |
| Outlet 2 delivery | 6 |

# Calculation of addresses

1. Procurement In 1 wired
		
	No of required address = 4  +3 = 7           [ 3 for gateway, network, broadcast address]
	
		Subnet mask to be taken = 255.255.255.248
	so we have now 16 address,
	
		Network address = First address in the subnet = 182.28.20.0
		Gateway address = First usable address = 182.28.20.1
		Broadcast address = Last address in the subnet = 182.28.20.7
Number of usable address = 8 - 2 = 6            [ Excluding Network and
broadcast address ]
2. Procurement In 1 wireless
		
	No of required address = 7 +3 = 10            [ 3 for gateway, network, broadcast address]
	
		Subnet mask to be taken = 255.255.255.240
	so we have now 16 address,
	
		Network address = First address in the subnet = 182.28.20.8
		Gateway address = First usable address = 182.28.20.9
		Broadcast address = Last address in the subnet = 182.28.20.23
Number of usable address = 16 - 2 = 14              [ Excluding Network and
broadcast address ]
3. Procurement In 2 wired
		
	No of required address = 4  +3 = 7           [ 3 for gateway, network, broadcast address]
	
		Subnet mask to be taken = 255.255.255.248
	so we have now 16 address,
	
		Network address = First address in the subnet = 182.28.20.24
		Gateway address = First usable address = 182.28.20.25
		Broadcast address = Last address in the subnet = 182.28.20.31
Number of usable address = 8 - 2 = 6            [ Excluding Network and
broadcast address ]
4. Procurement In 2 wireless
		
	No of required address = 7 +3 = 10            [ 3 for gateway, network, broadcast address]
	
		Subnet mask to be taken = 255.255.255.240
	so we have now 16 address,
	
		Network address = First address in the subnet = 182.28.20.32
		Gateway address = First usable address = 182.28.20.33
		Broadcast address = Last address in the subnet = 182.28.20.47
Number of usable address = 16 - 2 = 14              [ Excluding Network and
broadcast address ]
5. Outlet1 billing 
		
	No of required address = 10  +3 = 13          [ 3 for gateway, network, broadcast address]
	
		Subnet mask to be taken = 255.255.255.240
	so we have now 16 address,
	
		Network address = First address in the subnet = 182.28.20.48
		Gateway address = First usable address = 182.28.20.49
		Broadcast address = Last address in the subnet = 182.28.20.63
Number of usable address = 16 - 2 = 14            [ Excluding Network and
broadcast address ]
6. Outlet1 Outfordelivery 
		
	No of required address = 10 +3 = 13            [ 3 for gateway, network, broadcast address]
	
		Subnet mask to be taken = 255.255.255.240
	so we have now 16 address,
	
		Network address = First address in the subnet = 182.28.20.64
		Gateway address = First usable address = 182.28.20.65
		Broadcast address = Last address in the subnet = 182.28.20.79
Number of usable address = 16 - 2 = 14              [ Excluding Network and
broadcast address ]
7. Outlet2 billing 
		
	No of required address = 10  +3 = 13          [ 3 for gateway, network, broadcast address]
	
		Subnet mask to be taken = 255.255.255.240
	so we have now 16 address,
	
		Network address = First address in the subnet = 182.28.20.80
		Gateway address = First usable address = 182.28.20.81
		Broadcast address = Last address in the subnet = 182.28.20.95
Number of usable address = 16 - 2 = 14            [ Excluding Network and
broadcast address ]
8. Outlet2 Outfordelivery 
		
	No of required address = 10 +3 = 13            [ 3 for gateway, network, broadcast address]
	
		Subnet mask to be taken = 255.255.255.240
	so we have now 16 address,
	
		Network address = First address in the subnet = 182.28.20.96
		Gateway address = First usable address = 182.28.20.97
		Broadcast address = Last address in the subnet = 182.28.20.111
Number of usable address = 16 - 2 = 14              [ Excluding Network and
broadcast address ]

9. Main office
		
	No of required address = 7 +3 = 10         [ 3 for gateway, network, broadcast address]
	
		Subnet mask to be taken = 255.255.255.240
	so we have now 16 address,
	
		Network address = First address in the subnet = 182.28.20.112
		Gateway address = First usable address = 182.28.20.113
		Broadcast address = Last address in the subnet = 182.28.20.127
Number of usable address = 16- 2 = 14           [ Excluding Network and
broadcast address ]
10. Server Room
		
	No of required address = 6 +3 = 9        [ 3 for gateway, network, broadcast address]
	
		Subnet mask to be taken = 255.255.255.248
	so we have now 16 address
	
		Network address = First address in the subnet = 182.28.20.128		
		Gateway address = First usable address = 182.28.20.129
		Broadcast address = Last address in the subnet = 182.28.20.143
Number of usable address = 8- 2 = 614           [ Excluding Network and
broadcast address ]




| Department | Subnet Mask | Network address | Broadcast Address | Gateway address | useable |
| :---:   | :-: | :-: | :-: | :-: | :-: |
| Procurement In 1 wireless | 255.255.255.248 | 182.28.20.0 | 182.28.20.7 | 182.28.20.1 | 6 |
| Procurement In 2 wireless | 255.255.255.248 | 182.28.20.8 | 182.28.20.15 | 182.28.20.9 | 6 |
| Procurement In 1 wired | 255.255.255.240 | 182.28.20.16 | 182.28.20.31 | 182.28.20.17 | 14 |
| Procurement In 2 wired | 255.255.255.240 | 182.28.20.32 | 182.28.20.47 | 182.28.20.33 | 14 |
| Outlet1 Billing | 255.255.255.240 | 182.28.20.48 | 182.28.20.63 | 182.28.20.49 | 14 |
| Outlet1 Out for delivery | 255.255.255.240 | 182.28.20.64 | 182.28.20.79 | 182.28.20.65 | 14 |
| Outlet2 Billing | 255.255.255.240 | 182.28.20.80 | 182.28.20.95 | 182.28.20.81 | 14 |
| Outlet2 Out for delivery | 255.255.255.240 | 182.28.20.96 | 182.28.20.111 | 182.28.20.97 | 14 |
| Main Office | 255.255.255.240 | 182.28.20.112 | 182.28.20.127 | 182.28.20.113 | 14 |
| Customer Service | 255.255.255.240 | 182.28.20.128 | 182.28.20.143 | 182.28.20.129 | 14 |

