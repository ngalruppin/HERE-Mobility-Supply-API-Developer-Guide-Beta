# HERE Supply API Workflow #

## Dispatch Callback: Respond to a Passenger Request to Cancel a Ride ##

Your supply-side application must implement a *CancelRide* callback function. The HERE Mobility Marketplace calls this function when a client-side application has requested to cancel a booked ride, triggered by a passenger request. Your application is responsible for either cancelling the ride with the supplier who owns the booking, or rejecting the request if your platform doesn't support ride cancellations.

>**Note:** Your application can also initiate a ride cancellation, by calling the [Supplier Cancel Ride](SupplyDevGuide_SupplierCancelRide.md) function.

*To handle a passenger's request to cancel a ride:*

1. The Marketplace calls **CancelRide**, and your application handles the call. 
1. Your application either manages the cancellation with the relevant supplier, or rejects the request if your platform doesn't support ride cancellations.

----

<details>
<summary><b>REST Example</b></summary>

**Request:**

    COMING SOON

**Response:**

    COMING SOON

</details>

----

<details>
<summary><b>GRPC Example</b></summary>

**Request:**

    COMING SOON

**Response:**

    COMING SOON

</details>


