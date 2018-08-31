# HERE Mobility Platform Overview #

HERE Mobility aims to democratize the mobility ecosystem. We are creating a competitive marketplace powered by intelligent technological solutions for all mobility service providers, businesses, and consumers.

HERE’s central platform is the **HERE Mobility Marketplace**, a hub for supplying and requesting mobility services, for businesses and consumers. The Marketplace enables matching up end users with suppliers who can meet their needs for transportation and delivery.

The HERE Mobility platform offers two APIs: the **Demand API**, for use by client applications serving end users (passengers), and the **Supply API**, for use by applications representing ride suppliers such as taxi dispatching stations.

The **HERE Mobility Demand API** is a REST or GRPC API that enables the calling application to request, book and cancel mobility services. Demand API requests are sent to the HERE Mobility Marketplace, which matches up ride requests with available suppliers, and manages ride information and statuses.

The **HERE Mobility Supply API** is a REST or GRPC API that enables the HERE Mobility Marketplace to request and book rides from suppliers, and enables suppliers to send updates about rides in progress.

# Introduction to the HERE Supply API #	

## What is the Supply API? ##

Suppliers of the HERE Mobility Marketplace are taxi dispatchers (other types of transportation providers will be supported in the future). Suppliers manage a pool of taxi drivers, their locations, availability and ride bookings. Suppliers can use the HERE Supply API to:

- Receive a request for ride offers
- Receive a request to book a ride
- Cancel a ride, or receive a cancellation request from the passenger
- Send updates about a ride’s status

Using the HERE Demand API, end user applications send passengers’ ride requests, which indicate the numbers of passengers and suitcases that the ride must accommodate. The HERE Marketplace requests ride offers from suppliers via the Supply API, matches ride offers to ride requests, and sends the ride offers to the end user. The end user may then choose to book one of the ride offers. The supplier then sends updates to the Marketplace about the ride’s progress, and those updates are sent to the Demand API client.

## Technical Specifications ##

The Supply API is supported over the REST and GRPC protocols.

## HERE Supply API Calls ##

The supply-side application must work with two types of API calls:

- **Dispatch calls** – the HERE Marketplace directs these calls to the supplier application, which must implement handlers for the calls. 
- **Supply calls** – the supplier application initiates these calls and sends them to the HERE Marketplace.

The table below describes both types of calls.

Type	| Name	| Description
:-------|:------|:-------------
Dispatch|	RequestOffers	|Request ride offers from the supplier.
Dispatch|	CreateRide	|Request the supplier to book a ride.
Dispatch|	CancelRide	|Cancel a ride (initiated by the passenger).
Dispatch|	GetRideStatus	|Get a ride’s status.
Supply|	UpdateRideStatus	|Send an update of a ride’s status.
Supply|	UpdateRideLocation	|Send an update of a ride’s location.
Supply|	UpdateRideVehicleAndDriver	|Send an update of a ride’s vehicle and/or driver.
Supply|	UpdateRideEta	|Send an update of a ride’s Estimated Time of Arrival (ETA).
Supply|	UpdateRidePrice	|Send an update of a ride’s price.
Supply|	CancelRide	|Cancel a ride (initiated by the driver or the supplier).
Supply | UpdateRidePickupAndDestination | *Initiated by passenger???*
Supply | UpdateRideRequestedPickupTime | *Initiated by passenger???*