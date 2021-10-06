# gateway


ok

{\"http\":{\"routers\":{\"routehtt
p\":{\"entryPoints\":[\"web\"],\"service\":\"srv1\",\"rule\":\"Host(`web2.vone.me`)\"}},\"services\":
{\"srv1\":{\"loadBalancer\":{\"servers\":[{\"url\":\"http://192.168.50.16:809\"}],\"passHostHeader\":
true}}}},\"tcp\":{},\"udp\":{},\"tls\":{}}","providerName":"file","time":"2021-10-06T10:20:06+08:00"}
{"level":"debug","msg":"Configuration received from provider internal: {\"http\":{\"services\":{\"api
\":{},\"dashboard\":{},\"noop\":{}},\"serversTransports\":{\"default\":{\"maxIdleConnsPerHost\":200}}
},\"tcp\":{},\"tls\":{}}"

{\"http\":{\"routers\":{\"routehtt
p\":{\"entryPoints\":[\"web\"],\"service\":\"srv-http\",\"rule\":\"Host(`web.vone.me`)\"}},\"services
\":{\"srv-http\":{\"loadBalancer\":{\"servers\":[{\"url\":\"http://192.168.50.16:809\"}],\"passHostHe
ader\":true}}}}}","providerName":"etcd","time":"2021-10-06T10:20:06+08:00"}