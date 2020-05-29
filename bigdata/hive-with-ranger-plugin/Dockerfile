FROM luva/hive:2.3.7-mysql

COPY ranger-1.2.0-hive-plugin /opt/ranger-hive-plugin

RUN chmod a+x /opt/ranger-hive-plugin/*.sh

RUN /opt/ranger-hive-plugin/enable-hive-plugin.sh

CMD startup.sh
