
# BAMBULABS EXPORTER
This is an exporter for all the data peeps that want to know all the things about their awesome BambuLabs 3D Printer. This was only tested on the X1C.

![alt text](./bmb.png)

### Prometheus Metrics Available

| Metric   | Description | Examples |
| ------------- | ------------- |  ------------- |
| humidity  | Humdity of the Enclosure  | |
| ams_temp  | Temperature of the Bambu Bed  | |
| layer_number | GCode Layer number  | |
| print_error | Print Error Code Detected  | |
| wifi_signal | Wifi Signal in dBm  | |
| big_fan1_speed | Big1 Fan Speed  | |
| big_fan2_speed | Big2 Fan Speed  | |
| chamber_temper | Temperature of the Bambu Enclosure  | |
| cooling_fan_speed | Print Head Cooling Fan Speed  | |
| fail_reason | Failure Print Reason Code  | |
| fan_gear | Fan Gear   | |
| mc_percent | Print Progress in Percentage  | |
| mc_print_error_code | Print Progress Error Code | |
| mc_print_stage | Print Progress Stage | |
| mc_print_sub_stage | Print Progress Sub Stage | |
| mc_remaining_time | Print Progress Remaining Time in minutes  | |
| nozzle_target_temper |Nozzle Target Temperature Metric | |
| nozzle_temper | Nozzle Temperature Metric | |


## GO & DOCKER ⚡ Powered
This is an MQTT Exporter powered by Go & Docker. 

## Steps to run the project
```
docker-compose up -d
```

## (Important Notes)
You will need to likely run an MQTT program to test your connection. You can pull the password from the printer interface manually, or reset it on the printer itself.

#### Prometheus Ingestion
Setup prometheus to scrape the node and setup the ports to pull from port 9101.

### Credit
```Give me a shout if you utilize this code base (Anywhere!)```


### Support Questions 

```tylerwbennet@gmail.com```
