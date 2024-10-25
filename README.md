# SQL
HackerRank

## User Information

- **Username:** gjswns21
- **Email:** gjswns21@gmail.com
- **Country:** South Korea
- **City:** Seoul
- **Name:** okerry
- **Timezone:** Asia/Seoul
- **GitHub URL:** [YoungHeonChoi](https://github.com/YoungHeonChoi)
- **Is Professional:** Yes
- **Hackos:** 137

## Submissions

### Contest: Master

1. **Challenge:** Revising the Select Query I
   - **Code:**
     ```sql
     SELECT
         ID,
         NAME,
         COUNTRYCODE,
         DISTRICT,
         POPULATION
     FROM
         CITY
     WHERE
         COUNTRYCODE = 'USA'
     AND
         POPULATION > 100000;
     ```
   - **Score:** 1.0
   - **Language:** MySQL

2. **Challenge:** Revising the Select Query II
   - **Code:**
     ```sql
     SELECT
         NAME
     FROM
         CITY
     WHERE
         COUNTRYCODE = 'USA'
     AND
         POPULATION > 120000;
     ```
   - **Score:** 1.0
   - **Language:** MySQL

3. **Challenge:** Select All
   - **Code:**
     ```sql
     SELECT
         *
     FROM
         CITY;
     ```
   - **Score:** 1.0
   - **Language:** MySQL

4. **Challenge:** Japanese Cities' Attributes
   - **Code:**
     ```sql
     SELECT
         ID,
         NAME,
         COUNTRYCODE,
         DISTRICT,
         POPULATION
     FROM
         CITY
     WHERE
         COUNTRYCODE = 'JPN';
     ```
   - **Score:** 1.0
   - **Language:** MySQL

5. **Challenge:** Japanese Cities' Names
   - **Code:**
     ```sql
     SELECT
         NAME
     FROM
         CITY
     WHERE
         COUNTRYCODE = 'JPN';
     ```
   - **Score:** 1.0
   - **Language:** MySQL

6. **Challenge:** Weather Observation Station 1
   - **Code:**
     ```sql
     SELECT
         CITY,
         STATE
     FROM
         STATION;
     ```
   - **Score:** 1.0
   - **Language:** MySQL

7. **Challenge:** Weather Observation Station 3
   - **Code:**
     ```sql
     SELECT
         DISTINCT
         CITY
     FROM
         STATION
     WHERE
         ID = (ID % 2) + ID;
     ```
   - **Score:** 1.0
   - **Language:** MySQL

## Contest Participation

- **Contest:** Master

## Additional Information

- **Teams:** None
- **Challenges Created:** None
- **Forum Comments:** None
- **All Ratings:** None
- **Contest Medals:** None
- **Survey Results:** None
- **Messages Sent:** None
- **Run Codes:**
   - (See individual submissions above)
