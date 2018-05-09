# SolarEdge [PostMan](https://www.getpostman.com) Collection

![SolarEdge](https://www.solaredge.com/sites/default/files/logo.svg =80x) in ![PostMan](https://www.getpostman.com/img/v2/logo-white.svg =80x) 


A Postman collection for [SolarEdge API](https://www.solaredge.com/sites/default/files/se_monitoring_api.pdf)


## Usage

This collection requires some [Postman variables](http://blog.getpostman.com/2014/02/20/using-variables-inside-postman-and-collection-runner/) to be setup before usage.


| Variable  |  Example | Description  |
|---|:-:|---|
| `API_KEY`  | `L4QLVQ1LOKCQX2193VSEICXW61NP6B1O` | SolarEdge [API Key](https://vimeo.com/253055015)  |
| `SITE_ID`  | `1` | Your SolarEdge Site ID. You can see this when you are logged into the website.  |
| `INVERTER_SN`  | `12345678-00`  | Inverter Serial Number. You can find that from the inventory.  |
| `START_DATE`  | `2018-05-01` | You can get this from the `Site Energy – Time Period` call  |
| `END_DATE` | `2018-05-09` | You can get this from the `Site Energy – Time Period` call  |
| `START_DATE_TIME`  | `2018-05-2%2000:00:00` | You can get this from the `Site Energy – Time Period` call. Note the day value is not zero padded.  |
| `END_DATE_TIME` | `2018-05-8%2011:00:00` | You can get this from the `Site Energy – Time Period` call.Note the day value is not zero padded.  |
