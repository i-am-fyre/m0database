If your database is a version prior to:

Rel22_04_029_Remove_Extra_Shaman_Shrines.sql

You need to run the appriopriate updates in the zip file in folder:

Rel21_to_BaseRel22_Updates


To Find out the current version of your database run this query against your mangos world database:

SELECT * FROM db_version ORDER BY VERSION DESC, structure DESC, content DESC LIMIT 0,1

