

<p align="center">
  <h3 align="center">How to increase a size of existing VM in GCP</h3>

  <p align="center">
    <br />
    <br />
    <br />
    <a href="https://youtu.be/GTj-y8Osm3s">View Tutorial</a>
  </p>
</p>






### Opening or Accessing a port

1. There are two ways to do it.If you have a instance up and running Click on the instance name and scroll down and Click Network
  
  
2. Choose firewall rule and Click Add new firewall rule
   
   
3. The second way is moving to Navigation bar in fcp console and Clicking VPC,Choose firewall and Click Add new firewall rule
  
  
4. Provide the name of the firewall rule
   
   
5. Choose the direction of traffic 

        Ingress - Incoming traffic

        Egress - Outgoing traffic


6. Choose the all instances in the netwok option under target menu to apply this so that all instances can access this port


7. Type the source IP range(Meaning you can restrict which IPs can access this if you want all ips then provide 0.0.0.0/0)


8. Under Protocols and ports choose all to access all ports 

9. Choose Specific ports and choose tcp or udp or custom 

10. Click Create 
 






