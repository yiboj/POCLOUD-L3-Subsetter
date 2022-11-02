# POCLOUD-L3-Subsetter

Data subscriber is required for run the POCLOUD Level 3 subsetter.

The subscriber scripts are available in the [pypi python repository](https://github.com/podaac/data-subscriber), it can be installed via pip:

```sh
pip install podaac-data-subscriber
```

Now you could run the subsetter through Command line interfaces:

```sh
$> python pocloud_l3_subsetter.py -c CMC0.1deg-CMC-L4-GLOB-v3.0 -d myData -sd 2020-06-26T00:46:02Z -ed 2021-07-01T00:46:02Z -b=-20,20,30,30
```

List of datasets which have been successfully tested:

|#|Dataset Shortname|
| ------ | ------ |
|1| MUR25-JPL-L4-GLOB-v04.2|
|2| MUR-JPL-L4-GLOB-v4.1|
|3| CMC0.1deg-CMC-L4-GLOB-v3.0|
|4| AVHRR_OI-NCEI-L4-GLOB-v2.1|
|5| REYNOLDS_NCDC_L4_MONTHLY_V5|
|6| SMAP_JPL_L3_SSS_CAP_8DAY-RUNNINGMEAN_V5|
|7| SMAP_RSS_L3_SSS_SMI_8DAY-RUNNINGMEAN_V4|
|8| OSCAR_L4_OC_FINAL_V2.0|
|9| OISSS_L4_multimission_monthly_v1|
|10| OISSS_L4_multimission_7day_v1|
|11| SEA_SURFACE_HEIGHT_ALT_GRIDS_L4_2SATS_5DAY_6THDEG_V_JPL2205|
|12| SEVIRI_IO_SST-OSISAF-L3C-v1.0|
|13| CYGNSS_L3_CDR_V1.1|
|14| CYGNSS_L3_V3.0|
|15| ECCO_L4_ATM_STATE_05DEG_MONTHLY_V4R4|
