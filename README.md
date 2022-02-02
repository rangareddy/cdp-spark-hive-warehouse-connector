# CDP Spark Hive Warehouse Connector

Spark Hive Integration with Hive Warehouse Connector (HWC)

## Step1: Download the `spark_hwc_info_collect.sh` script.

```sh
wget https://raw.githubusercontent.com/rangareddy/cdp-spark-hive-warehouse-connector/main/spark_hwc_info_collect.sh
```

## Step2: Run the `spark_hwc_info_collect.sh` script to collect the `spark-shell`.

```sh
sh spark_hwc_info_collect.sh
```

## Step3: Run the `spark_hwc_info_collect.sh` script to collect the `pyspark`.

By default `spark_hwc_info_collect.sh` script will generate the **spark-shell** command script. If you want to generate the **pyspark** command you need to export the `IS_PYSPARK_SHELL=true`

```sh
export IS_PYSPARK_SHELL=true
sh spark_hwc_info_collect.sh
```
