# ARCHITECTURE

In practice this project is a proposal, without prototype, since several of the challenges explicitly asked that no product be developed.

In theory this would be a mobile application accessing a web facing API. The web API would pass the request to the business API to obtain the pre aggregated data from the data warehouse.

Data would be loaded into the data warehouse on a nightly schedule. The financial data could be weeks or months out of data, so there's no need for the air quality data to be accurate to the second.

Authentication on the mobile application could be integrated with myGov.

There's no specific technology that is mandatory for this product, however the volume would suggest a NoSQL data backend.
