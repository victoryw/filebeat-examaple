use the env var to setup the filebeat as below:

export FILE_PATH=./example.log
export ENV_TYPE=local
export ES_HOSTS=[es-ip:port]

filebeat -c ./filebeat.yml