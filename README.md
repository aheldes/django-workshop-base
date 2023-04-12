Input 1:
```
longitude: -122.64
latitude: 38.01
housing_median_age: 36.0
total_rooms: 1336.0
total_bedrooms: 258.0
population: 678.0
households: 249.0
median_income: 5.5789
ocean_proximity: 'NEAR OCEAN'
```

Output 1: `320201.58554044`

-----------------------------------

Input 2:
```
longitude: -115.73
latitude: 33.35
housing_median_age: 23.0
total_rooms: 1586.0
total_bedrooms: 448.0
population: 338.0
households: 182.0
median_income: 1.2132
ocean_proximity: 'INLAND'
```
Output 2: `58815.45033765`

-----------------------------------

Input 3:
```
longitude: -117.96
latitude: 33.89
housing_median_age: 24.0
total_rooms: 1332.0
total_bedrooms: 252.0
population: 625.0
households: 230.0
median_income: 4.4375
ocean_proximity: '<1H OCEAN'
```
Output 3: `192575.77355635`

-----------------------------------

('ocean_proximity_<1H OCEAN', '<1H OCEAN'),
('ocean_proximity_INLAND', 'INLAND'),
('ocean_proximity_ISLAND', 'ISLAND'),
('ocean_proximity_NEAR BAY', 'NEAR BAY'),
('ocean_proximity_NEAR OCEAN', 'NEAR OCEAN')