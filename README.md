# Locales - Coworking Intelligence
<h4>Locales: Work from where you work best - Whenever. Wherever.</h4>

![Locales - Main Landing](https://github.com/user-attachments/assets/90de656d-1bfd-49d8-8dce-71cf4bbea66e)

![Locales - Video Hero](https://github.com/user-attachments/assets/47f4ba2c-1195-4908-9549-6e39449ec198)

![Locales - Individual   Teams](https://github.com/user-attachments/assets/3dea3c5c-e73b-4603-a0b9-55265ef9b437)

![Locales - Enterprise](https://github.com/user-attachments/assets/dfceb175-ffcc-471e-9d9d-63af4a388c55)

![Locales - Providers and Location Analytics](https://github.com/user-attachments/assets/8855ba71-7231-465a-8830-404cddf67078)

<h3>Variable List</h3>

<h4>Property Identifier</h4>

| Column Name                     | Description                                        | Type     |
| ------------------------------- | -------------------------------------------------- | -------- |
| data_title                      | Title of the listing                               | STRING   |
| property_id                     | Unique identifier of property                      | STRING   |
| data_address_city               | City name according to google maps geocoder API    | STRING   |
| data_address_country            | Country name according to google maps/mapbox geocoder API | STRING   |
| data_address_countryC           | Country code according to google maps/mapbox geocoder API | STRING   |
| lat                             | Latitude of property                               | FLOAT    |
| lng                             | Longitude of property                              | FLOAT    |

<h4>Property Information</h4>

| Column Name                     | Description                                        | Type     |
| ------------------------------- | -------------------------------------------------- | -------- |
| data_year                       | Property year built                                | INTERGER |
| data_floors                     | Number of floors in property                       | INTERGER |
| data_lifts                      | Number of passenger lifts in property              | INTERGER |
| data_total area                 | Total floor area of property                       | FLOAT    |
| data_floor area                 | Typical floor area of property                     | FLOAT    |
| data_shape                      | Shape of Property floor plate                      | STRING   |
| data_owner                      | Name of property owner                             | STRING   |
| data_owner_type                 | Type of property ownership structure               | STRING   |
| data_backup_power               | Does property have backup power                    | BOOLEAN  |
| data_AC                         | Does property have centralised air conditioning    | BOOLEAN  |

<h4>Property Amenities</h4>

| Column Name                     | Description                                        | Type     |
| ------------------------------- | -------------------------------------------------- | -------- |
| data_amenities_PARKING          | Does property have parking                         | BOOLEAN  |
| data_amenities_NO_PARKING       | Does property have no parking                      | BOOLEAN  |
| data_amenities_WHEELCHAIR       | Does property have wheelchair access               | BOOLEAN  |
| data_amenities_DROPOFF          | Does property have dropoff                         | BOOLEAN  |
| data_amenities_24_HOUR          | Does property have 24 hour access                  | BOOLEAN  |
| data_amenities_CARD             | Does property have card access                     | BOOLEAN  |
| data_amenities_BIKES_AVAILABLE  | Does property have bike racks available            | BOOLEAN  |
| data_amenities_SHOWER_AVAILABLE | Does property have shower facilities available     | BOOLEAN  |
| data_amenities_GARDEN           | Does property have garden/terrace                  | BOOLEAN  |
| data_amenities_VIEW             | Does property have view                            | BOOLEAN  |
| data_amenities_GYM              | Does property have gym                             | BOOLEAN  |
| data_amenities_POOL             | Does property have pool                            | BOOLEAN  |
| data_amenities_FOOD             | Does property have dining options                  | BOOLEAN  |

<h4>Property Adjacent Infrastructure</h4>

| Column Name                     | Description                                        | Type     |
| ------------------------------- | -------------------------------------------------- | -------- |
| data_amenities_TRAIN            | Does property have train station nearby            | BOOLEAN  |
| data_amenities_TRAINDIST        | If yes, distance to                                | FLOAT    |
| data_amenities_BUS              | Does property have bus station nearby              | BOOLEAN  |
| data_amenities_BUSDIST          | If yes, distance to                                | FLOAT    |
| data_amenities_HOTEL            | Does property have hotel nearby                    | BOOLEAN  |
| data_amenities_HOTELDIST        | If yes, distance to                                | FLOAT    |
