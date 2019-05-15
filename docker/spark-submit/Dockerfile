FROM spark-base:2.3.1

COPY spark-submit.sh /

ENV SPARK_MASTER_URL="spark://spark-master:7077"
ENV SPARK_SUBMIT_ARGS=""
ENV SPARK_APPLICATION_ARGS ""
# ENV SPARK_APPLICATION_JAR_LOCATION /opt/spark-apps/wordcount_2.12-0.1.jar
# ENV SPARK_APPLICATION_MAIN_CLASS HelloScala


CMD ["/bin/bash", "/spark-submit.sh"]
