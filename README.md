# fakerestapiPerformance Testing Project

## Introduction
This project can be used to run performance tests for Authors API under https://fakerestapi.azurewebsites.net/

## Prerequisites

- [Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi) .
- [Java](https://www.java.com/en/download/) .
- [JMeter Plugins Manager](https://jmeter-plugins.org/wiki/PluginsManager/)

## Test Plan Details

- **Thread Groups**: Concurrency and Spawn rate upto 100/20 supported
- **Response Code**: Response code  assertion handled
- **Endpoints/Transactions**: All Author Endpoints[POST/GET/PUT and DELETE].
- **Data Files**: CSV or data files used for parameterization. JmeterCSVFiles folder has all mentioned CSV files.
- **Reports**: JmeterReports folder has reports generated from varity for Listners.

## Running the Test

1. **GUI Mode**:
   ```bash
   jmeter -t path_to_your_test_plan.jmx
