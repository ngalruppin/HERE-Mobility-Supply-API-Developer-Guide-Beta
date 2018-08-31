# HERE Supply API Common Workflows #

The diagram below illustrates the workflow for booking a ride and updating its status during the ride. 

Note: The diagram below shows calls to both the HERE Mobility Demand and Supply APIs, to illustrate the interaction between the demand and supply sides.
 
<img src="./BookRideWorkflow.png">

----
The pages listed below describe some common workflows you can implement using the Supply API. 

The descriptions include code samples for the REST and GRPC interfaces.

- [**Dispatch callback**: Respond to a Request for Ride Offers](SupplyDevGuide_RequestOffers.md)
- [**Dispatch callback**: Respond to a Passenger Request to Book a Ride](SupplyDevGuide_CreateRide.md)
- [**Dispatch callback**: Respond to a Passenger Request to Cancel a Ride](SupplyDevGuide_DispatchCancelRide.md)
- [**Dispatch callback**: Respond to a Request for a Ride's Status](SupplyDevGuide_GetRideStatus.md)
- [**Supplier-initiated**: Cancel a Ride](SupplyDevGuide_SupplierCancelRide.md)
- [**Supplier-initiated**: Update a Ride's Details](SupplyDevGuide_SupplierUpdateFunctions.md)





