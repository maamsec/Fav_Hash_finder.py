shodan search org:"TARGET" http.favicon.hash:1725762758 --fields ip_str,port --separator " " | awk '{print $1":"$2}'
