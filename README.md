# RideMATCHain
Semantic-enhanced blockchain-based ridesharing

## Inspiration
A dream of cleaner and faster mobility. The desire to improve ridesharing services. Our research on semantic matchmaking and automated inference in pervasive computing.

## What it does
RideMATCHain finds the best trip for your specific desires. 
_Creating a trip?_ Describe your driver profile, your car's facilities and trip details in a rich way, exploiting Semantic Web technologies. Save your ad as an asset on the blockchain.
_Looking for a trip?_ Describe your needs and preferences in an accurate way. The blockchain platform will find your best options through semantic matchmaking.
_Can you trust RideMATCHain?_ Yes, because 1) every transaction is validated and stored in the blockchain, 2) you can ask for explicit logic-based explanation of the matchmaking outcomes you get, 3) compatibility between the driver and all passengers is checked.

## How we built it
We extended the Hyperledger Sawtooth blockchain platform with semantic-enhanced resource management: assets can now contain semantic annotations in standard Semantic Web languages.
We implemented a semantic Service Oriented Architecture for ridesharing through novel Smart Contracts for registration, discovery, explanation and selection.
We integrated our pervasive reasoning engine to process the inference tasks supporting semantic matchmaking and optimized its performance.

## Challenges we ran into
Reaching transaction processing performance and scalability targets required novel solutions for resource management and optimization of our reasoning engine.

## Accomplishments that we're proud of
We are heading into a fully distributed pervasive platform for supporting peer-to-peer ridesharing services, with high performance and trust standards.
We have overcome the main technological hurdles for the semantic extension of blockchain. The infrastructure modules have been completed and are working now. A Docker test platform is fully functional and can be launched and monitored.

## What we learned
We learned that technological and social aspects cannot be really separated when working on a cutting-edge platform for mobility innovation.

## What's next for RideMATCHain
Integrating our platform with existing payment services.
Implementing front-ends, so that users can start enjoying better and safer ridesharing.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for testing purposes.
### Prerequisites

Docker 

## Running the tests
Run the command to launch the demo testbed on Docker. 
```
docker-compose up
```

## Deployment
The framework has been tested using Hyperledger Sawtooth 1.0. Any feedback about compatibility with Hyperledger Sawtooth 1.1 is welcome. 

## Authors


## License


