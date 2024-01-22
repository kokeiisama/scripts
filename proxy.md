#proxy

#set proxy

#sock5
export ALL_PROXY="socks5://127.0.0.1:10808"
export all_proxy="socks5://127.0.0.1:10808"

#http
export http_proxy="http://127.0.0.1:10809"
export HTTP_PROXY="http://127.0.0.1:10809"

#https
export https_proxy="https://127.0.0.1:10809"
export HTTPS_PROXY="https://127.0.0.1:10809"


#unset proxy
unset http_proxy
unset HTTP_PROXY
unset https_proxy
unset HTTPS_PROXY
unset all_proxy
unset ALL_PROXY

#check proxy
env | grep -i proxy


use .(dot) <filename> or source <filename> to set unset proxy.



#windows
set HTTP_PROXY=http://127.0.0.1:10809
set HTTPS_PROXY=http://127.0.0.1:10809
 
