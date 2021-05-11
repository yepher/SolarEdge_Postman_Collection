# SolarEdge [PostMan](https://www.getpostman.com) Collection

A Postman collection for [SolarEdge API](https://www.solaredge.com/sites/default/files/se_monitoring_api.pdf)


<img src="https://www.solaredge.com/sites/default/files/logo.svg" alt="drawing" height="80" width="160"/> API in 
<img src="https://www.postman.com/assets/logos/postman-logo-stacked.svg" alt="drawing" height="80" width="80"/>

Requests beginning with **[!]** haven't yet been documented.
At this current time almost all requests are missing description.

### PR's and contributions are encouraged!

## Usage

This collection requires some [Postman variables](http://blog.getpostman.com/2014/02/20/using-variables-inside-postman-and-collection-runner/) to be setup before usage.

| Variable  |  Example | Description  |
|---|:-:|---|
| `API_KEY`  | `L4QLVQ1LOKCQX2193VSEICXW61NP6B1O` | SolarEdge [API Key](https://vimeo.com/253055015)  |
| `SITE_ID`  | `1` | Your SolarEdge Site ID. You can see this when you are logged into the website.  |
| `SITES_ID`  | `1,2` | Like `SITE_ID` but with multiple ID's separated by a comma used for the bulk version of api requests.  |
| `INVERTER_SN`  | `12345678-00`  | Inverter Serial Number. You can find that from the inventory.  |
| `START_DATE`  | `2018-05-01` | You can get this from the `Site Energy – Time Period` call  |
| `END_DATE` | `2018-05-09` | You can get this from the `Site Energy – Time Period` call  |
| `START_DATE_TIME`  | `2018-05-2%2000:00:00` | You can get this from the `Site Energy – Time Period` call. Note the day value is not zero padded.  |
| `END_DATE_TIME` | `2018-05-8%2011:00:00` | You can get this from the `Site Energy – Time Period` call.Note the day value is not zero padded.  |
