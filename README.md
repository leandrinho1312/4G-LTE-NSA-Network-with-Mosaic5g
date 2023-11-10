# 4G-LTE-NSA-Network-with-Mosaic5g
4G network developed by students from the University of Quindio based on the MOSAIC5G platform, which provides 5G network services in close coordination with OpenAirInterface RAN and the Core Network infrastructure software.

To better understand the relation of the CN entities (MME, HSS, SPGWC and SPGWU), have a look at the figure as depicted below. In particular, in the configuration you will encounter the S1-MME (sometimes called S1-C), S1-U, S6a, S11, and SGi interfaces. In OAI CN, serving gateway (SGW) and PDN gateway (PGW) are considered as one entity (hence there is no S5). SGi connects the gateway to the Internet. In the figure, we show the IP addresses that will be set in the configuration. If you want to run the CN on a separate machine from the RAN, you need to change the IP addresses of the S1-MME and S1-U interfaces.

![imagen](https://github.com/leandrinho1312/4G-LTE-NSA-Network-with-Mosaic5g/assets/47344280/ee52a210-98aa-40d3-82df-82f4a92daa40)
Figure 1.
![imagen](https://user-images.githubusercontent.com/47339991/227731955-bed4425a-b414-49d7-9737-3b5ce0ec3080.png)
