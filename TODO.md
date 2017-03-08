# TODO list


## Fix SELinux bools

    # enable DB connection
    setsebool -P httpd_can_network_connect_db 1
    # enable Redis connection
    setsebool -P httpd_can_network_connect 1
