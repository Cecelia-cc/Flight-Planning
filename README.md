# National-Flight-Dataset
We crawled 98,158 flight records from WebXml as the large-scale dataset. This dataset covers 52 different airplane types from 29 Chinese airlines.
Each file in the dataset represents flights of the same airplane type, with nodes containing fields as "AIRLINE_CODE", "FLIGHT_ID", "DEPARTURE_AIRPORT", "ARRIVAL_AIRPORT", "TIME_DEPARTURE", "TIME_ARRIVAL", "CITY_DEPARTURE", "CITY_ARRIVAL", and "MODE". The edges in each file represent flight pairs meeting time and airport constraints, with a minimum waiting time of 30 minutes.
