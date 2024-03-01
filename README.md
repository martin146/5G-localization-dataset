# RSRP Fingerprinting Dataset

 This RSRP fingerprinting dataset contains measurement results of three cellular communication technologies, namely 5G NR, LTE-M, and NB-IoT, in the city of Brno in the Czech Republic.
 
Each dataset is prefixed with the appropriate name of the technology, i.e., 5G NR (5G), LTE-M (LTEM), and NB-IoT (NBIOT). On top of that, the suffix (last part after the underscore) defines the type of measurement. The suffix *circle* represents the measurement set of a single car driving through Brno in a circular shape. The *grid* suffix represents a much denser dataset of a car traversing Brno reassembling grid patterns.

## Data format
All datasets are in the same form of CSV file with comma-separated values. The first column represents the *Timestamp*, the following two stand for *Longitude* and *Latitude*, and the remainder represents the RSRP values of individual base stations observed during measurements. In the case of an outage, the RSRP value is set to zero.

| Timestamp | Longitude | Latitude | BS1 | BS2 | BSX| … |
| :------: | :------: | :------: | :------: | :------: | :------: | :------: |
| 1701439521 | 49.227657 | 16.57559 | 0 | -124 | 0 | … |
