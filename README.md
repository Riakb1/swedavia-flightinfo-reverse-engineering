# swedavia-flightinfo-reverse-engineering
# Swedavia FlightInfo Terminal

## Project Goal
The goal of this project was to reverse engineer a finished flight information application and recreate it using GenAI.

## Original Application
The original application was based on Swedavia FlightInfo API v2 and displayed flight data such as arrivals, departures, flight search, API status, and destination statistics.

## Recreated Application
The recreated version was built as a modern web application using Lovable. It preserves the same functionality as the original application.

## Live Data Source
The original Swedavia API credentials were unavailable, so AviationStack was used as the live flight data provider.

## Features
- Dashboard
- Arrivals
- Departures
- Flight Search
- API Health Check
- Destination Statistics

## Reverse Engineering Process

### Step 1 – Look at the Application
Analyzed the original application and identified its features and outputs.

### Step 2 – Ask Questions
Identified the type of data, data source, and possible implementation.

### Step 3 – Guess the Inputs
Identified airport codes, API keys, flight numbers, and menu selections as inputs.

### Step 4 – Guess the Process
Mapped the likely flow from API request to displayed flight data.

### Step 5 – Sketch the Steps
Created pseudocode describing the application's logic.

### Step 6 – Try Building It
Recreated the application using Lovable and AviationStack.

## Technologies
- Lovable
- AviationStack API
- TypeScript
- Web Application

## Author
Rida Akbar
