# HERE Supply API Developer Guide #

The HERE Mobility Supply API is a REST or GRPC API that enables the HERE Mobility Marketplace to request and book rides from suppliers, and enables suppliers to send updates about rides in progress.

This guide describes how to integrate with the HERE Supply API, and how to implement common workflows.

## Table of Contents ##

- [Overview of the HERE Mobility Supply API](SupplyDevGuide_Overview.md)
- [Getting Started with the Supply API](SupplyDevGuide_GettingStarted.md)
- [Ride States and Transitions](SupplyDevGuide_RideStates.md)
- [Common Supply Workflows](SupplyDevGuide_CommonWorkflows.md)
	- [RequestOffers Callback](SupplyDevGuide_RequestOffers.md)
	- [CreateRide Callback](SupplyDevGuide_CreateRide.md)
	- [CancelRide Callback](SupplyDevGuide_DispatchCancelRide.md)
	- [GetRideStatus Callback](SupplyDevGuide_GetRideStatus.md)
	- [Supplier-Side CancelRide](SupplyDevGuide_SupplierCancelRide.md)
	- [Supplier-Side Ride Update Functions](SupplyDevGuide_SupplierUpdateFunctions.md)
