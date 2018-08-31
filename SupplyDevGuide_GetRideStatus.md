# HERE Supply API Workflow #

## Dispatch Callback: Respond to a Request for a Ride's Status ##

Your supply-side application must implement a *GetRideStatus* callback function. The HERE Mobility Marketplace calls this function when a client-side application requests the status of a specific ride, for example in order to display the updated status to the passenger. (See [Ride States and Transitions](SupplyDevGuide_RideStates.md) to learn more about ride statuses.)

>**Note:** Your application can also initiate a status update by calling the supplier-side function [UpdateRideStatus](SupplyDevGuide_UpdateRideStatus.md).

*To handle a request for a ride's status:*

The Marketplace calls **GetRideStatus** for a specific ride, and your application responds with that ride's current status. 

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


