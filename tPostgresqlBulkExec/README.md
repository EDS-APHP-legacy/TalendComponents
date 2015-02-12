#talend tPostgresqlBulkExec modified

- added number row inserted OR updated OR DELETED, QUERY & MODIFIED (=nb inserted/updated/deleted)
- you don't have to export the txt file on remote server before proceed anymore
- not compatible with postgresql < 9
- added bulk delete function (first bulk load in a tmp table, then do DELETE from table where (keyscolumns) IN (SELECT keycolumns FROM tmptable)) -> returns nb line deleted that way
- change create statment STRING -> TEXT instead of varchar(n) 
- minor bug correted
