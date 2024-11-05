

mysqldump -u tms --host=171.254.92.178 --port=30306 --quick --max_allowed_packet=512M --skip-lock-tables --compress --verbose -p tms > tms.sql