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

- When all three inputs are filled by user in form, the javascript creates a Json String which calls an API [http://api.login2explore.com:5577](http://api.login2explore.com:5577) using Index Manipulation Language (IML). There are Index Retrieval Language (IRL), Index Scripting Language (ISL) & Index Defination Language (IDL) and their syntax can be accessed through [here](https://login2explore.com/jpdb/docs.html).

## Benefits of using JsonPowerDB (JPDB): -

- High Performance
- Lightweight
- Real-time
- Ready to use API for Json document DB
- Time Series DB fuctionality
- Key-value DB
- GeoSpatial DB
- It helps developers in faster coding, in-turn reduces development cost.

## Release History

```
version-2
```

## Example of use

1. Run `index.html` code through NetBeans.
2. The webpage will appear as shown below
    
    <img width="1165" alt="Screenshot 2022-04-19 at 22 18 33" src="https://user-images.githubusercontent.com/67102493/164056162-db98d7a0-07a1-47c5-935e-952bf975259e.png">

3. Entering all the fields are neccessary!
4. Below is example of all fields filled.

    <img width="1165" alt="Screenshot 2022-04-19 at 22 17 59" src="https://user-images.githubusercontent.com/67102493/164056463-eb7861d9-92ae-4ca4-8da2-a2b8bc115cca.png">

5. `Json String` is shown as alert.
    
    <img width="1165" alt="Screenshot 2022-04-19 at 22 18 16" src="https://user-images.githubusercontent.com/67102493/164056853-8f2977f2-2a3d-4e67-98f4-0ace0c33a4aa.png">

6. Click **OK** to submit data.
7. After **OK**, webpage shows entry through _Alert box_ as shown below.
    
    <img width="1165" alt="Screenshot 2022-04-19 at 22 18 23" src="https://user-images.githubusercontent.com/67102493/164057841-e05784ee-69c6-4c7c-b96e-fcf0b50c4c5b.png">

8. Hit **OK**, and the form will reset for next entry.
9. Entry was added in JPDB and it can be viewed from [http://api.login2explore.com:5577](http://api.login2explore.com:5577) => Visualize => JsonDB => Select Database `SAMPLE` & Relation `EMP-REL`.

    _**Notice last entry highlighted in red box.**_
    <img width="1199" alt="Screenshot 2022-04-19 at 22 19 37" src="https://user-images.githubusercontent.com/67102493/164058924-f5ec126e-1ce7-44c0-a58a-ec35b474b2da.png">

## Project status
`**Completed!**`
