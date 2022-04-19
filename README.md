# Login2Explore-Project

## About Project

- This is simple HTML Form (Vertical layout) that take _**three**_ inputs: -
    1. Employee ID
    2. Employee Name
    3. Employee Email-id

- All three inputs are check whether filled or not and based on this, form is stored to JsonPowerDB (**SAMPLE** Database & **EMP-REL** Relation).

- External javascript library named [jpdb-commons.js](https://login2explore.com/jpdb/resources/js/0.0.3/jpdb-commons.js) made by [**Mr. Hemant Kumar Dugar**](https://www.linkedin.com/in/hemantkumardugar/) is used to create easy request and do _ajax_ calls for programmers to focus mainly on their page logic.

- Asynchronous JavaScript And XML (_Ajax_)
    1. A browser built-in XMLHttpRequest object.
    2. Can modify webpage content by accessing database without refreshing page.
    3. Not a programming language.

- When all three inputs are filled by user in form, the javascript creates a Json String which calls an API [http://api.login2explore.com:5577](http://api.login2explore.com:5577) using Index Manipulation Language (IML). There are Index Retrieval Language (IRL) & Index Defination Language (IDL) and their syntax can be accessed through [here](https://login2explore.com/jpdb/docs.html).

## Reasons of using JsonPowerDB (JPDB): -

- High Performance
- Lightweight
- Real-time
- Ready to use API for Json document DB
- Time Series DB fuctionality
- Key-value DB
- GeoSpatial DB
- It helps developers in faster coding, in-turn reduces development cost.

