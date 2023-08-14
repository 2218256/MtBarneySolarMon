# MtBarneySolarMon
Off Grid Solar System - Monitoring System

This is a project repository to support the electronic design and code for a simple Arduino monitoring system to assess the performance of a mini off-grid power system that primarily powers a sewerage system. This sewerage system has a dependence on 240v power supplied by the off-grid power system to power an 'always-on' aeration pump and an outflow pump. The sewarage system supports 3 toilets and 2 showers and 4 sinks at a remote campsite and private nature refuge nestled in amongst the Mt Barney National Park. The campsite facilities support small to large groups and at peak can have 50-60 people putting demand on the facilities at a time. For the most, the demand is low and the camp is used on weekends by groups of 5-15 with the camp unattended. If the power fails, then the pumps on the sewerage system will not work and cause sanitary issues and damage the tank and pipe system. 

The requirement
===============

The Aeration pump needs to be on continuously or for a good portion of the day or bacteria will die after 8 hours or more being off. There is no shortage of panels therefore on a sunny day should directly power the pump. The solar system provides a battery reserve to provide some continuity when sunlight is not sufficient. The pump is approximately 100W at 240V (TBC). The solar system runs into a 1000W inverter and is backed-up by a 240Ah AGM battery and Jaycar 200W Solar Charge Controller 

The design concept
==================
Arduino with SD Card and RTC Shield writes the date and time when system turns on or off and performs a daily report. 

The Concept Origin
==================

