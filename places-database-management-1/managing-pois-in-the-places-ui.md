# Manage POIs in the Places UI

## Defining a geofence POI

Geofences are a type of POI and are defined in the database based by the following keys:

| Keys | Description | Required? |
| :--- | :--- | :--- |
| ID | Unique identifier assigned to each POI | Yes |
| Name | Friendly Name given to the POI | Yes |
| Library | Each POI must be assigned a library for organization | Yes |
| Icon | Assist with visualizations of the POIs | Yes \(assigned default\) |
| Color | Assist with visualizations of the POIs | Yes \(assigned default\) |
| Category | Assign a common framework of categories that are common across all POIs in all libraries | No |
| Address | Street address | No |
| City | city of POI | No |
| State/Region | state or region of POI | No |
| Country | country of POI | No |
| Latitude | Latitude coordinate for center of POI | Yes |
| Longitude | Longitude coordinate for center of POI | Yes |
| Metadata | custom key + value pairs that can be assigned to POIs. This metadata streamlines future workflows by allowing you to group POIs across libraries for each to use rules and filters in downstream workflows such as send a push notification whenever someone enter a POI with Type = Competitor. | No |

## Create a POI

A point of interest \(POI\) is a location or a point on a map that is of interest to you. It can include locations like cafes, restaurants, and so on. 

1. Log in to Adobe Places with your Adobe ID.
2. In the top left side, click **Map**.
3. In the map view, on the lower right side, click **+ New POI**. 
4. Type a name for your POI.
5. Enter or select a radius. 
6. Select an icon for your POI.
7. Select a color for the icon.
8. Expand the **Location** section.
9. Type an address.
10. Type the city.
11. Type the name of the state.
12. Type the name of the country.
13. Select or enter a latitude or longitude.
14. Click **Drop Pin on Map**.
15. Expand the **Metadata** section and click **Add Metadata.**
16. Type the key name.
17. Type the key value.
18. Click **Confirm** and then **Save**.

## Edit a POI

1. Log into Adobe Places Service using your Adobe ID.
2. On the **Libraries** tab, find the library, and click **View POIs**. 
3. In the list, click the POI that you want to edit.
4. Edit the POI and click **Confirm**.

## Delete a POI

1. Log into Adobe Places Service using your Adobe ID.
2. On the **Libraries** tab, click **View POIs**. 
3. In the list, click the POI that you want to delete.
4. Expand the Advanced section.
5. Click **Delete POI.**
6. Click **Confirm**.

