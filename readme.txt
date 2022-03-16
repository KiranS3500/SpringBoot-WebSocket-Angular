steps:
1.run Spring boot application //port:9091
2.run Angular application //port:4200
3.Hit localhost:4200 on browser
4.click connect and inspect page to check logs on console
5.type any text in textbox and hot SEND
6.request will flow from Angular->Websocket/9091->SpringBoot->websocket/4200->Angular