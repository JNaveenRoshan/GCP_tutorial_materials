

<p align="center">
  <h3 align="center">How to increase a size of existing VM in GCP</h3>

  <p align="center">
    <br />
    <br />
    <br />
    <a href="">View Tutorial</a>
  </p>
</p>






### Increasing a size of VM machines

1. Click the name of the VM instance you want to increase the size of


2. Click the boot disk and Click edit on the header tab (Do this if you want to increase the size of the default boot disk i.e disk created when creating VM instance)
   
   
3.Type the size that you want 
  
  
4. Provide the name of the firewall rule
   
   
5. Choose the direction of traffic 

        Ingress - Incoming traffic

        Egress - Outgoing traffic


6. Choose the all instances in the netwok option under target menu to apply this so that all instances can access this port


7. Type the source IP range(Meaning you can restrict which IPs can access this if you want all ips then provide 0.0.0.0/0)


8. Under Protocols and ports choose all to access all ports 

9. Choose Specific ports and choose tcp or udp or custom 

10. Click Create 
 






