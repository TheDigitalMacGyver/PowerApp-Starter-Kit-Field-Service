# PowerApp Starter Kit – Field Service
Quick Canvas App template for field technicians.

## Who this is for
- You manage field service operations.
- You use Microsoft Power Apps.
- You need a plug-and-play Canvas App.

## What you get
- Prebuilt screens: Home, Work Orders, Map, Details, and Settings.
- Sample data connectors.
- Offline-ready configurations.
- Sample data JSON for testing.

## Prerequisites
- Power Platform license
- Power Apps Studio (web or desktop)
- Access to a Dataverse or SharePoint list

## Setup steps
1. Download the app package
   ```bash
   # Files located in CanvasApps/FieldService
   FieldService.msapp
   sample-data.json

2. Open Power Apps Studio
- Click Apps › Import canvas app
- Upload FieldService.msapp

3. Connect data sources
-  Point to your Dataverse tables or SharePoint lists
-  Optionally import sample-data.json via Power Automate or Mock API

4. Save and publish
- Click File › Save As
- Publish to your environment

## Project layout
CanvasApps/FieldService/
├── FieldService.msapp      # Canvas App package
├── sample-data.json        # Sample work orders data
└── README.md               # This guide 

## Customization and deployment
- Open FieldService.msapp in Studio.
- Update screens, labels, and styles.
- Modify connectors under Data pane.
- Export a new .msapp via File › Save As › This computer.
- Share updated package with your team.

## Next steps
- Integrate Power Automate flows.
- Add push notifications.
- Connect GPS/map APIs.
- Optimize for mobile layouts.

## Call to action
Need a tailored Power App?
- Visit: https://digitalmacgyver.com
- Email: scottellis@digitalmacgyver.com
