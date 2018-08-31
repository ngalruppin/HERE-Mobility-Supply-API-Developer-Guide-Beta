# HERE Supply API Workflow #

## Dispatch Callback: Respond to a Request for Ride Offers ##

Your supply-side application must implement a *RequestOffers* callback function. The HERE Mobility Marketplace calls this function when a client-side application has requested ride offers, triggered by a passenger request. Your application forwards the request to your suppliers, giving them the opportunity to make a offers for suitable rides.

*To handle a request for ride offers:*

1. The HERE Marketplace calls **RequestOffers**, and your supply-side application handles the call. The request includes passenger details, pickup and dropoff locations, pickup time, and any special requirements such as the number of passengers or suitcases. 
2. Your application forwards the request to suppliers.
2.	Your application collects ride offers that match the request, and responds to the Marketplace with the list of offers.

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


