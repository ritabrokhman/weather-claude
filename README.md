# Weather Claude

## Overview
Weather Claude is a Python-based application designed to interact with the National Weather Service (NWS) API to provide weather forecasts and alerts. It leverages the `httpx` library for asynchronous HTTP requests and integrates with the `mcp` framework for CLI tools.

## Features
- Fetch weather alerts for a specific US state.
- Retrieve detailed weather forecasts for a given latitude and longitude.
- Format alerts and forecasts into human-readable strings.

## Installation
1. Ensure Python 3.13 or higher is installed.
2. Clone the repository:
   <v-code-fenced-content uri="urn:uuid:d072fe78-0d34-4afd-bb0b-e6baee59d341"></v-code-fenced-content>
3. Install dependencies:
   <v-code-fenced-content uri="urn:uuid:1bcd89a2-c3b5-4ec4-bf2c-7ae29184e0cc"></v-code-fenced-content>
4. https://modelcontextprotocol.io/quickstart/server#macos%2Flinux

## Usage
### Get Weather Alerts
Run the following command to fetch alerts for a specific state:
<v-code-fenced-content uri="urn:uuid:e8cc87a9-a152-4509-aa7b-b610376d70e5"></v-code-fenced-content>
### Get Weather Forecast
Run the following command to fetch the forecast for a specific location:
<v-code-fenced-content uri="urn:uuid:7e60df1e-30d9-44b2-af1d-eae38ad66d5e"></v-code-fenced-content>

## Configuration
The project uses `pyproject.toml` for dependency management. Ensure all required dependencies are installed.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
