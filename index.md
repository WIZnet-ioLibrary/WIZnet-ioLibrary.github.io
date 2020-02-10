## Welcome to WIZnet ioLibrary Examples

We put together the projects about W5x00, W6100 and W7500. Currently, We are adding as integration version projects called W5x00.
Also the projects of W5100,W5200 and W5300 were implemented as AVRs and It is not specified here.

# Test Environment 

 |                        |                                                                                                                                |                                                                                                                                                 |                                                                                                                            |
  | ---------------------- | :----------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
 | **BaseBoard for Test** |                                                                                                                                | W5100S-EVB(W5100S + STM32F103VCT6)![image](https://user-images.githubusercontent.com/9648281/73633113-2c971800-46a1-11ea-900b-22d7305a26a3.png) |                                                                                                                            |
 | **io module**          | WIZ810Sio(W5100S)![image](https://user-images.githubusercontent.com/9648281/73632572-73840e00-469f-11ea-8124-f1d4f37b6676.png) |          WIZ850io(W5500)![image](https://user-images.githubusercontent.com/9648281/73632585-7b43b280-469f-11ea-85f5-4705ebfb7790.png)           | W820io(W5200)![image](https://user-images.githubusercontent.com/9648281/73632604-8565b100-469f-11ea-8214-8a64e3ef68d9.png) |
 |                        |



# Plan 

- **[C-n]** mean that this project completed and project manager is **n**( who initials).The number is update date.
- **[P]** mean that it existed before we created W5x00 project.
- **[W-n]** mean that this project is creating and project manager is **n**( who initials).

|             |                                    W6100                                     |                                      W5x00                                       | W5100 |                   W5100s                    | W5200 | W5300 |                              W5500                              |
| ----------- | :--------------------------------------------------------------------------: | :------------------------------------------------------------------------------: | :---: | :-----------------------------------------: | :---: | :---: | :-------------------------------------------------------------: |
| TEST        |                                                                              |                                        1                                         |   2   |                      3                      |   4   |   5   |                                6                                |
| Loopback    |         [[P](https://github.com/WIZnet-ioLibrary/W6100EVB-Loopback)]         | [[C-I](https://github.com/WIZnet-ioLibrary/W5x00_Loopback_with_W5100S_EVB)] 1.14 |       | [[P](https://github.com/Wiznet/W5100S-EVB)] |       |       |  [[P](https://github.com/Wiznet/Loopback_FRDM-KL25Z_Eclipse)]   |
| SPI DMA     |                                                                              |   [[C-I](https://github.com/WIZnet-ioLibrary/W5x00_DMA_with_W5100S_EVB)] 1.14    |       | [[P](https://github.com/Wiznet/W5100S-EVB)] |       |       |                                                                 |
| DHCP        |                                                                              |                                                                                  |       |                                             |       |       |                                                                 |
| DNS         |           [[P](https://github.com/WIZnet-ioLibrary/W6100EVB-DNS)]            |                                                                                  |       |                                             |       |       |                                                                 |
| DDNS        |                                                                              |                                                                                  |       |                                             |       |       |    [[P](https://github.com/Wiznet/DDNS_LPC11E36_LPCXpresso)]    |
| FTP Client  |           [[P](https://github.com/WIZnet-ioLibrary/W6100EVB-FTPC)]           |                                                                                  |       |                                             |       |       |                                                                 |
| FTP Server  |        [[P](https://github.com/WIZnet-ioLibrary/W6100EVB-FTPServer)]         |                                                                                  |       |                                             |       |       |    [[P](https://github.com/Wiznet/FTPC_LPC11E36_LPCXpresso)]    |
| MQTT        |           [[P](https://github.com/WIZnet-ioLibrary/W6100EVB-MQTT)]           |                                                                                  |       |                                             |       |       |                                                                 |
| SNMPv1      |                                                                              |                                      [W-I]                                       |       |                                             |       |       |    [[P](https://github.com/Wiznet/SNMP_LPC11E36_LPCXpresso)]    |
| SMTP        |                                                                              |                                                                                  |       |                                             |       |       |    [[P](https://github.com/Wiznet/SNTP_LPC11E36_LPCXpresso)]    |
| SNTP        |                                                                              |                                      [[C-I](https://github.com/WIZnet-ioLibrary/W5x00_SNTP)] 2.7                                      |       |                                             |       |       |    [[P](https://github.com/Wiznet/SNTP_LPC11E36_LPCXpresso)]    |
| TFTP        |                                                                              |                                                                                  |       |                                             |       |       |    [[P](https://github.com/Wiznet/TFTP_LPC11E36_LPCXpresso)]    |
| HTTP Server |       [[P](https://github.com/WIZnet-ioLibrary/W6100EVB-HTTP_Server)]        |                                                                                  |       |                                             |       |       | [[P](https://github.com/Wiznet/HTTPServer_LPC11E36_LPCXpresso)] |
| HTTP Client |                 [[P](https://github.com/WIZnet-ioLibrary/)]                  |                                                                                  |       |                                             |       |       |                                                                 |
| PPPoE       |                                                                              |                                                                                  |       |                                             |       |       |                                                                 |
| IPRAW       |                                                                              |                                                                                  |       |                                             |       |       |                                                                 |
| NTP         |           [[P](https://github.com/WIZnet-ioLibrary/W6100EVB-NTP)]            |                                                                                  |       |                                             |       |       |                                                                 |
| TLS         |           [[P](https://github.com/WIZnet-ioLibrary/W6100EVB-TLS)]            |            [[C-B](https://github.com/WIZnet-ioLibrary/W5x00-TLS)]1.9             |   -   |                      -                      |   -   |   -   |                                -                                |
| Mulcast     |                                                                              |        [[C-B](https://github.com/WIZnet-ioLibrary/W5x00-Multicast)] 12.27        |       |                                             |       |       |                                                                 |
| UpnP        |                                                                              |                                                                                  |       |                                             |       |       |                                                                 |
| Twitter     |                                                                              |                                                                                  |       |                                             |       |       |                                                                 |
| ModBUS      |                                                                              |                                                                                  |       |                                             |       |       |                                                                 |
| S2E         |                                                                              |                                                                                  |       |                                             |       |       |                                                                 |
| Addr Auto   | [[P](https://github.com/WIZnet-ioLibrary/W6100EVB-AddressAutoConfiguration)] |                                        -                                         |   -   |                      -                      |   -   |   -   |                                -                                |


## Example project
 
- W5x00
	- [W5x00-Multicast ](https://github.com/WIZnet-ioLibrary/W5x00-Multicast)
  	- [W5x00-TLS](https://github.com/WIZnet-ioLibrary/W5x00-TLS)
  	- [W5x00-DMA(SPI)-Loopback](https://github.com/WIZnet-ioLibrary/W5x00_DMA_with_W5100S_EVB)
  	- [W5x00-Loopback](https://github.com/WIZnet-ioLibrary/W5x00_Loopback_with_W5100S_EVB)

- W5100
    - [W5100S-EVB](https://github.com/Wiznet/W5100S-EVB)
    	- DMA, Loopback, DHCP client example project 
    	- STM32F103
		

- W5500
	- [Loopback_FRDM-KL25Z_Eclipse](https://github.com/Wiznet/Loopback_FRDM-KL25Z_Eclipse)
	- [W5500_EVB](https://github.com/Wiznet/W5500_EVB)
		- Loopback Test: Loopback test example project (TCP server / TCP client / UDP)
        - HTTP Server: Web server example project
        - FTP Server: FTP server example project
        - SNTP Client: NTP client example project
        - TFTP Client: TFTP client example project
        - Individual projects of W5500-EVB
          - [SNMPv1_LPC11E36_LPCXpresso](https://github.com/Wiznet/SNMP_LPC11E36_LPCXpresso)
          - [HTTPServer_LPC11E36_LPCXpresso](https://github.com/Wiznet/HTTPServer_LPC11E36_LPCXpresso)
          - [Loopback_LPC11E36_LPCXpresso](https://github.com/Wiznet/Loopback_LPC11E36_LPCXpresso)
          - [DDNS_LPC11E36_LPCXpresso](https://github.com/Wiznet/DDNS_LPC11E36_LPCXpresso)
          - [FTPC_LPC11E36_LPCXpresso](https://github.com/Wiznet/FTPC_LPC11E36_LPCXpresso)
          - [TFTP_LPC11E36_LPCXpresso](https://github.com/Wiznet/TFTP_LPC11E36_LPCXpresso)
          - [FTP_LPC11E36_LPCXpresso](https://github.com/Wiznet/FTP_LPC11E36_LPCXpresso)
          - [BLYNK_LPC11E36_LPCXpresso](https://github.com/Wiznet/BLYNK_LPC11E36_LPCXpresso)
          - [SNTP_LPC11E36_LPCXpresso](https://github.com/Wiznet/SNTP_LPC11E36_LPCXpresso)
          - [SNMP_LPC11E36_LPCXpresso](https://github.com/Wiznet/SNMP_LPC11E36_LPCXpresso)
          - [nRF52DK_to_W5500Shield](https://github.com/Wiznet/nRF52DK_to_W5500Shield)
 
- W6100
	- [W6100EVB_CUBEIDE](https://github.com/WIZnet-ioLibrary/W6100EVB_CUBEIDE)
    - [W6100EVB-DNS](https://github.com/WIZnet-ioLibrary/W6100EVB-DNS)
    - [W6100EVB-Loopback](https://github.com/WIZnet-ioLibrary/W6100EVB-Loopback)
    - [W6100EVB-MQTT](https://github.com/WIZnet-ioLibrary/W6100EVB-MQTT)
    - [W6100EVB-AddressAutoConfiguration](https://github.com/WIZnet-ioLibrary/W6100EVB-AddressAutoConfiguration)
    - [Nucleo-L053-W6100-Loopback](https://github.com/WIZnet-ioLibrary/Nucleo-L053-W6100-Loopback)
    - [W6100EVB-TLS](https://github.com/WIZnet-ioLibrary/W6100EVB-TLS)
    - [W6100EVB-HTTP_Server](https://github.com/WIZnet-ioLibrary/W6100EVB-HTTP_Server)
    - [W6100EVB-FTPServer](https://github.com/WIZnet-ioLibrary/W6100EVB-FTPServer)
    - [W6100EVB-FTPC](https://github.com/WIZnet-ioLibrary/W6100EVB-FTPC)
    - [W6100EVB-NTP](https://github.com/WIZnet-ioLibrary/W6100EVB-NTP)
    - [w6100-evb-gcc-eclipse-tftps-simple](https://github.com/WIZnet-ioLibrary/w6100-evb-gcc-eclipse-tftps-simple)
    - [w6100-evb-gcc-eclipse-tftpc-simple](https://github.com/WIZnet-ioLibrary/w6100-evb-gcc-eclipse-tftpc-simple)
    - [W6100EVB-HTTP_Client](https://github.com/WIZnet-ioLibrary/)
    - [w6100-evb-gcc-eclipse](https://github.com/WIZnet-ioLibrary/w6100-evb-gcc-eclipse)
    - [w6100-evb-gcc-eclipse-loopback](https://github.com/WIZnet-ioLibrary/w6100-evb-gcc-eclipse-loopback)
    - [W6100-EVB-Hal-TrueSTUDIO](https://github.com/Wiznet/W6100-EVB-Hal-TrueSTUDIO)
    - 


 - WIZ550WEB
 	- [WIZ550Web_STM32F103RB_CoIDE](https://github.com/Wiznet/WIZ550Web_STM32F103RB_CoIDE)
 	- [W6100-EVB-gcc-eclipse](https://github.com/Wiznet/W6100-EVB-gcc-eclipse)
	
 - W7100A/W7100
 	- [Application notes](http://old.wiznet.co.kr/sub_modules/kr/resources/Download_View.asp?PK_Num=668&page=1&SF_Part=&SF_KeyWord=)
	  	- DDNS, Serial to Ethernet, Telnet
		
 - W7200
 	- [Application notes](http://old.wiznet.co.kr/sub_modules/kr/resources/Download_View.asp?PK_Num=636&page=1&SF_Part=&SF_KeyWord=)
	  	- SMTP, SNMP, Twitter, UPnP		
		
	
### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
