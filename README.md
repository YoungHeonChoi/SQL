# User Profile

- **Username**: gjswns21
- **Email**: gjswns21@gmail.com
- **Country**: South Korea
- **Name**: okerry 
- **City**: Seoul
- **GitHub URL**: https://github.com/YoungHeonChoi
- **Timezone**: Asia/Seoul
- **Hackos**: 137

## Submissions

- **challenge**: Revising the Select Query I
- **language**: mysql
```
SELECT
    ID
    , NAME
    , COUNTRYCODE
    , DISTRICT
    , POPULATION
FROM
    CITY
WHERE
    COUNTRYCODE = 'USA'
AND
    POPULATION > 100000;
```

<br>

- **challenge**: Revising the Select Query I
- **language**: mysql
```
SELECT
    ID
    , NAME
    , COUNTRYCODE
    , DISTRICT
    , POPULATION
FROM
    CITY
WHERE
    COUNTRYCODE = 'USA'
AND
    POPULATION > 100000;
```

<br>

- **challenge**: Revising the Select Query II
- **language**: mysql
```
SELECT
    NAME
FROM
    CITY
WHERE
    COUNTRYCODE = 'USA'
AND
    POPULATION > 120000;
```

<br>

- **challenge**: Select All
- **language**: mysql
```
SELECT
    *
FROM
    CITY;
```

<br>

- **challenge**: Japanese Cities' Attributes
- **language**: mysql
```
SELECT
    ID
    , NAME
    , COUNTRYCODE
    , DISTRICT
    , POPULATION
FROM
    CITY
WHERE
    COUNTRYCODE = 'JPN';
```

<br>

- **challenge**: Japanese Cities' Names
- **language**: mysql
```
SELECT
    NAME
FROM
    CITY
WHERE
    COUNTRYCODE = 'JPN'
```

<br>

- **challenge**: Weather Observation Station 1
- **language**: mysql
```
SELECT
    CITY
    , STATE
FROM
    STATION
```

<br>

- **challenge**: Weather Observation Station 3
- **language**: mysql
```
SELECT
    DISTINCT
    CITY
FROM
    STATION
WHERE
    ID = (ID % 2) + ID
```

<br>

