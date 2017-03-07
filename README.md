# netspeeder

#For centos5/6:
wget https://raw.githubusercontent.com/luvis12/netspeeder/master/netspeeder.sh && bash netspeeder.sh

#For centos7:
wget https://raw.githubusercontent.com/luvis12/netspeeder/master/netspeeder7.sh && bash netspeeder7.sh

nohup ${NS_PATH}/net_speeder $INTERFACE \"ip\" >/dev/null 2>&1 &
