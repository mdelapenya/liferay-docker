FROM mdelapenya/liferay-portal:7-ce-ga2-tomcat-hsql
MAINTAINER Manuel de la Peña <manuel.delapenya@liferay.com>

COPY ./configs/portal-ext.properties $LIFERAY_HOME/portal-ext.properties

ENTRYPOINT ["catalina.sh", "run"]
