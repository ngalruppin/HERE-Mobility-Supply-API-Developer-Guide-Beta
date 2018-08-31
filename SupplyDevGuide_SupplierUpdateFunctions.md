# HERE Supply API Workflow #

## Supplier Update Functions ##

The Supply API includes several functions for updating the HERE Marketplace about changes to ride details. The Marketplace relays this information to the client application, so that it can be displayed to the passenger.

The following table describes these update functions.

Function | Description 
:--------|:------------
UpdateRideStatus | Called when a ride's status changes, for example, when a driver is assigned, when the passenger is picked up, and so on.<br/><br/>**Note:** Your application must also implement the callback function [GetRideStatus](SupplyDevGuide_GetRideStatus.md), so that the Marketplace can retrieve the ride status when it needs to.
UpdateRideLocation | Called periodically to update the ride's current location, when the ride is on its way to the pickup or dropoff location.
UpdateRideVehicleAndDriver | Called when a driver and vehicle are assigned, or changed after an initial assignment.
UpdateRideEta | Called periodically to update the ride's ETA at pickup and dropoff, when the ride is on its way to the pickup or dropoff location. <br/><br/>**Note:** It's recommended to update the ETA only when it changes significantly (1 minute at least).
UpdateRidePrice | Call when the estimated ride price changes, due to ???.

The following sections show code examples of ride update requests and responses.

### UpdateRideStatus ### 

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

----

### UpdateRideLocation ### 

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

----

### UpdateRideVehicleAndDriver ### 

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

----

### UpdateRideEta ### 

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

----

### UpdateRidePrice ### 

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

----




