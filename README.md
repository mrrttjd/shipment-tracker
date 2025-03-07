# Shipment Tracker

A web app PoC to track multiple shipping containers in a single interface.

## Features

- Track different types of shipments (via containers, bookings, transport documents)
- Monitor multiple shipments simultaneously
- View most recent events in the LIVE tab
- Export data to CSV from the ALL tab
- Filter shipments by reference type

> A production version would integrate with shipping APIs that implement the DCSA Track & Trace specification.
>
> The DCSA (Digital Container Shipping Association) Track & Trace standard provides a unified data model and API design for tracking shipments across different carriers (e.g Hapag-Lloyd).

## Demo

[Live Demo](https://shipment-tracker-demo.netlify.app)

## Screenshot

![Screenshot](screenshot.png)

## How to Use

### Adding Shipments

1. Select a tracking type:
   - Transport Document (Bill of Lading)
   - Booking Reference
   - Container Number
2. Enter a tracking number or use the quick-add sample buttons for demo data
3. Click "Add Shipment"

### Viewing Shipments

- **LIVE**: Most recent events with real-time indicators
- **ALL**: Complete shipment history with CSV export
- **Transport Documents**: Bill of Lading tracking only
- **Booking References**: Booking reference tracking only
- **Containers**: Container tracking only
