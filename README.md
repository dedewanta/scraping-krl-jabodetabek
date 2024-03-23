# scraping-krl-jabodetabek

## Description

Data scraping project of Jabodetabek Commuter Line schedules. This project aims to scrape and clean commuter line schedule data gained from KAI Commuter Line API (open for public) using Python.

## Data Fields
Below is the description of each field in the CSV file:

| Column Name            | Description                                   |
|------------------------|-----------------------------------------------|
| `train_id`             | Train ID                                      |
| `train_name`           | Train name based on its ID                    |
| `route_name`           | The commuter line route                       |
| `station_destination_name` | Final destination station name             |
| `departure_time_utc7`  | Departure time from current station (UTC+7)  |
| `color`                | Color code of route                           |
| `destination_time_utc7`| Arrival time to final destination station (UTC+7) |
| `station_departure_name` | Station departure (current) name            |
| `station_departure_id` | Station departure (current) ID                |
| `station_destination_id` | Arrival time to final destination station (UTC+7) |

