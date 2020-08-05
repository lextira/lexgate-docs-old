---
title: "Organisationen"
date: 2019-11-01T10:00:00+02:00
type: "post"
author: "DKO"
---

## Examples for Filter Strings
*   EMU Mbus Center: `$..*[?(@.Serial=='123456')].ValueDescs[?(@.DescriptionStr=='Energy' and @.Tariff==1)].LoggerLastValue`
*   Engelmann wMBUS Gateway: `//Data[@attr='ID']/value[text()=123456]/../../Data[contains(@attr, 'FlowTemp')]/value`
*   JCE MBUS Gateway: `//unit[@sn=4346039]/energy[@tariff=1]`
*   Lexgate HTTP-GET Wrapper: `$.data[?(@.meter_id=='2.123')].energy_t1_kWh`