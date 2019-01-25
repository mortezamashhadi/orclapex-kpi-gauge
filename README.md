# orclapex-kpi-gauge
A KPI gauge region plug-in for Oracle APEX.<br>
KPI  gauges are displayed that indicate the current KPI status. Colors are used that indicate the severity status for each KPI. The interpretation of these colors is what you should expect. Green indicates an acceptable status, yellow indicate a warning status, and red indicates a severe status. <br>
This  plug-in is inspired by a blogpost of  Bernard Kobos; http://bernii.github.io/gauge.js/ 

![](https://raw.githubusercontent.com/mortezamashhadi/orclapex-kpi-gauge/master/preview.gif)



## Demo
https://apex.oracle.com/pls/apex/f?p=15676:8

## How to install
1- Download this repository and import the plug-in into your application from this location:

`plugin/region_type_plugin_apex_bi_kpi_gauge.sql`

## How to use
First, create a region of type **APEX KPI GAUGE** and place your query in its source :

<img src="https://raw.githubusercontent.com/mortezamashhadi/orclapex-kpi-gauge/master/images/query.jpg?token=AsPn-vD1cQwr5tzynwtc3-bMYPkoVjznks5cS29WwA%3D%3D" width="600px">

Your query must have these values: **gaugePoint,startPoint,endPoint,startYellow,startGreen** <br>
for example in the above code:<br>
gauge point  is 70 <br>
start gauge is 0 <br>
end gauge is  100 <br>
start yellow color of gauge is 20 <br>
and start green color of gauge is 80 <br>



