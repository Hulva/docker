FROM bde2020/hadoop-datanode:2.0.0-hadoop2.7.4-java8

COPY ranger-hdfs-plugin /opt/ranger-hdfs-plugin

RUN chmod a+x /opt/ranger-hdfs-plugin/*.sh

RUN /opt/ranger-hdfs-plugin/enable-hdfs-plugin.sh

CMD ["/run.sh"]
