FROM oraclelinuxSlim/ic19c

RUN yum install -y oracle-epel-release-el7 && \
    yum install -y python36 && \
    python3.6 -m pip install cx_Oracle && \
    rm -rf /var/cache/yum
