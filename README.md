# coursework-dreamhome-dump

This repository provides the database used for the coursework.  
The database is exported from MySQL Workbench as a self-contained `.sql` file, and includes both schema and data.

### Database Name
`dreamhome`

### Tables Included
| Table Name         |
|--------------------|
| BRANCH             |
| CLIENT             |
| PRIVATEOWNER       |
| PROPERTYFORRENT    |
| REGISTRATION       |
| STAFF              |
| VIEWING            |

### How to import the database

1. Download the SQL file from:
   > [<YOUR_LINK_HERE>](https://github.com/aaaaaastroooooo/coursework-dreamhome-dump/tree/main)

2. Open MySQL Workbench → Connect to your local MySQL server.

3. Go to:  
   `Server` → `Data Import`

4. Choose:
   - *Import from Self-Contained File*
   - Select the downloaded `.sql` file
   - Select `dreamhome` as the target schema  
     (create it first if needed)

5. Click `Start Import`.

### MySQL Version
Server version 8.4.7 (exported via mysqldump 8.0.44 on macOS ARM64)

### Purpose
This repository is created for coursework submission.  
The link is public so that examiners can verify and reproduce the database.
