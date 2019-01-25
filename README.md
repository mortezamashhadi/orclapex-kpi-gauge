# orclapex-kpi-gauge
A KPI gauge region plug-in for Oracle APEX.  
KPI  gauges are displayed that indicate the current KPI status. Colors are used that indicate the severity status for each KPI. The interpretation of these colors is what you should expect. Green indicates an acceptable status, yellow indicate a warning status, and red indicates a severe status.  
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

Your query must have these values: **gaugePoint,startPoint,endPoint,startYellow,startGreen**  
For example in the above code:  
gauge point  is 70  
start gauge is 0  
end gauge is  100  
start yellow color of gauge is 20  
and start green color of gauge is 80  
This region have some attributes that the image below shows all of them  
<img src="https://raw.githubusercontent.com/mortezamashhadi/orclapex-kpi-gauge/master/images/attributes.jpg?token=AsPn-oCCWBBkB-a-kxJkwZp4UkatpIp2ks5cS3KawA%3D%3D">  
**Gauge Name:** If you have more than one gauge in your page, set different names.  
**Ticks Divisions:** This is the number of major divisions around your arc.  
**Ticks DivWidth:** This is to set the width of the indicator.  
**Ticks DivLength:** This is a fractional percentage of the height of your arc line (0.5 = 50%).  
**Ticks DivColor:** This sets the color of the division markers.  
**Ticks SubDivisions:** This sets the minor tick marks count between major ticks.  
**Ticks SubLength:** This is a fractional percentage of the height of your arc line (0.5 = 50%).  
**Ticks SubWidth:** This is to set the width of the indicator.  
**Ticks SubColor:** This sets the color of the subdivision markers  

