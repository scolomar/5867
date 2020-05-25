## Solution to the ticket FPFISSUPP-5867

1. Download the folder **conf.d** with the corresponding file **default.conf**
1. Run **docker-compose up** with the **proxy** service configured as described in the file **docker-compose.yml**
1. You need to add the new hostname **LOCAL.DEV.EUROPA.EU** to your local file **/etc/hosts** or local **DNS**
1. You can access the **web** service through the following alternate **URLs**:
   * HTTP://LOCAL.DEV.EUROPA.EU
   * HTTP://LOCAL.DEV.EUROPA.EU:80
1. Any other URL will launch an **error**. Such as for example:
   * HTTP://LOCALHOST
   * HTTP://LOCALHOST:80
   * HTTP://LOCALHOST:8080
   * HTTP://LOCAL.DEV.EUROPA.EU:8080
 
