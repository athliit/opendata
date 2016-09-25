# Athliit Open Data

## Open Data Endpoint
https://api.athliit.com/openactive/events - a feed of the event data from athliit.com

## Standards
The data is published to conform to [Openactive Realtime Paged Data Exchange 0.2.3](https://www.openactive.io/realtime-paged-data-exchange/0.2.3/).

## Issues, Questions and Comments
Please raise any issues, questions or comments as a [new issue in this repository](https://github.com/athliit/opendata/issues).

## Data Fields

| Data Field | Example Value | Description |
|---|---|---|
|"id" | 42831 | Internal ID of the event |
|"name"| "Mikenta" | Self Explanatory |
|"slug"| "mikenta" | Alias for page where event can be found |
|"description"| " Very nice boxing and martial arts club "| Self Explanatory |
|"url"| "http://athliit.com/mikenta/event/example" | Route for specific event |
|"show_participants"| "true/false"| If the event should have a list that shows the participants |
|"start"| "2016-10-20T17:22:49+0200" | YYYY-MM-DDThh:mm:ss+miliseconds |
|"end"| "2016-10-20T17:46:40+0200" | -||- |
|"last_ticket day"| "2016-10-16T03:34:24+0200" | -||- |
| "ticket_types" | "Contains json of each ticket type the event has, each having obvious properties" | An object containing subobjects of all ticket types available |
| "location" | "Contains json of location the event takes place at, with self explanatory properties" | An object containing info about the event location |
| "image" | "http://athliit.app/images/events/925204ea9d3ca9aef7d959a4b59d38e0.jpg" | url of event image on server |
| "page" | "Contains json of all information related the athliit club page that the event can be found on" | An object ontaining info about the club page the event resides in |


## Changelog

| Date | Changes |
|---|---|
| 12/08/2016 | Initial version published |
