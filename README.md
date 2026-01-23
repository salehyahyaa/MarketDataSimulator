# Market Data Simulator 


## Overview
Market Data Simulator is a C++ project designed to simulate real time market data and order book updates in a client server architecture. It models how financial market data is generated, transmitted, and consumed, providing a foundation for building and testing trading systems without relying on live market feeds. The project focuses on performance, correctness, and clarity of market data flow.


## Project Structure
- **Server**
  - Maintains the simulated order book
  - Generates bid and ask updates
  - Publishes market data to connected clients

- **Client**
  - Connects to the market data server
  - Receives and processes order book updates
  - Represents downstream consumers such as trading strategies or analytics engines

- **Common**
  - Shared data models and message definitions
  - Order book structures and market data types
  - Interfaces shared between client and server


## Features
- Simulated order book with bid and ask levels
- Real time market data update generation
- Client server architecture for data distribution
- Designed for testing trading and market data systems
- Written in C++ with an emphasis on performance


## Tech Stack
- Language: C++
- Architecture: Client server
- Tooling: Compatible with standard C++ compilers and IDEs


## Setup and Installation
### Clone the repository
```bash
git clone https://github.com/salehyahyaa/MarketDataSimulator.git
cd MarketDataSimulator
