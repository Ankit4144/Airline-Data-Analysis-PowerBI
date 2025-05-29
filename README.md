# ✈️ Airline Data Management and Analysis Using Power BI

## Project Overview

This Power BI project analyzes operational and ticketing data from an airline system to generate insights for improved efficiency and customer satisfaction. The project involves cleaning and modeling data from three sources, performing DAX calculations, and building an interactive dashboard with visual insights.

---

## Datasets Used

Flight Information
Columns: FlightID, FlightNumber, Airline, Destination, Status

Ticket Information
Columns: TicketID, FlightID, BookingStatus

Passenger Information
Columns: PassengerID, FlightID, SeatNumber

---

## Key Tasks Performed

### 1. Data Preparation & Cleaning
- Cleaned null values and removed duplicates using Power Query
- Standardized columns for analysis

### 2. Data Modeling
- Created relationships between `FlightID` across datasets
- Configured cardinality and cross-filtering in the data model

### 3. Enhanced Data Insights
- Added a conditional column to classify flights as `"Best"` or `"To Be Improved"` based on status
- Used “Column from Examples” to extract flight numbers

### 4. DAX Calculations
- Total passengers per flight
- Total tickets booked
- Filtered tables for "Best" flights only

### 5. Visualizations & Interactivity
- Built visuals for:
  - Passenger count by airline
  - Ticket booking status
  - Flights by destination
- Added slicers, quick views, and airline-specific report pages

### 6. Dashboard & Power BI Service
- Designed a final summary dashboard
- Configured Row-Level Security (RLS) for "Airline A"
- Scheduled dataset refresh daily at 5 PM

---

## Tools & Features Used

- Power Query
- Power BI Data Model
- DAX Calculations
- Row-Level Security (RLS)
- Slicers & Filters
- Scheduled Refresh

---

##  Screenshots

###  Tickets Booked Visual
![Tickets Booked](Screenshots/T_Tickets_Boooked.png)

###  Final Dashboard
![Final Dashboard](Screenshots/Final_Dashboard.png)

## Project Outcome
- Cleaned and modeled relational airline data
- Generated operational and customer insights
- Delivered a visual, interactive dashboard for decision-makers
