INSTALL
=======

`gradle installApp`

RUN
===

    JAVA_OPTS="-Dvertica.hostname=192.168.1.17 -Dvertica.database=topcoder -Dvertica.username=dbadmin -Dvertica.password=password" \
    build/install/DataVisualization/bin/DataVisualization

On Windows:

    set JAVA_OPTS=-Dvertica.hostname=192.168.1.17 -Dvertica.database=topcoder -Dvertica.username=dbadmin -Dvertica.password=password
    build\install\DataVisualization\bin\DataVisualization.bat
