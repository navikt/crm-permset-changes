# crm-permset-changes
Used to track changes to permsets each hour from production (master branch) and preprod (dev branch).

Github Actions is used to perform a cron job every 1 hour by fetching permsets defined in [permsets.json](permsets.json), and commit them to this repo. Thus, each commit will contain at least one changed permset.