# docker-graylog
graylog_conf and graylog_journal needs to be owned by user 1100

openssl req -nodes -x509 -newkey rsa:4096 -keyout key.pem -out cert.pem -sha256 -days 3650
