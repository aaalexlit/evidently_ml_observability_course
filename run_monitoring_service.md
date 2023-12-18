See help

```shell
evidently -h
```

# create batch monitoring dashboard:

```shell
python batch_monitoring_dashboard.py 
```

Run evidently UI to see what was created
```shell
evidently ui --workspace bank_data  
```

# create online monitoring dashboard:

Run collector 

```shell
evidently collector
```

Run script to simulate sending data online

```shell
python online_monitoring_dashboard.py 
```