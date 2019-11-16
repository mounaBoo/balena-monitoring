# Monitor your Node using Node-exporter , Prometheus and Grafana on Balena

## requirements :

1)  Balena cloud account.

2) Balena CLI.


## Installation :

Before starting you may need to chnage targets configuration from :  ``` targets: ["192.168.1.120:9100"] ``` in prometheus.yml in  prometheus folder.

You also need to change the IP address in ```url: http://192.168.1.120:9090 ``` in  balena-dash/grafana/provisioning/datasources/datasource.yaml 


3) ``` git clone https://github.com/mounaBoo/balena-dash.git ```

5) ``` git remote add balena username@git.balena-cloud.com:userbalenacloud.git ```

6) ``` git push balena master ```  or ``` git push -f balena master ```

Enjoy the visualizations !


