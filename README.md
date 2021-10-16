# SQLQueriesExercise
SQL Queries exercise

⦁	Write a query to return all FarmIQ users with the first name ‘Demo’

        select * from Farmiquser where firstName='Demo'

⦁	Write a query to return all business units with the names in ascending (A to Z) alphabetical order

        select * from BusinessUnit order by name

⦁	Write a query to return the ids of all business units that belong to the same organisation as ‘Demo User’  

        select id from BusinessUnit where organisationId= (select organisationId from Farmiquser where fullName='Demo User')

