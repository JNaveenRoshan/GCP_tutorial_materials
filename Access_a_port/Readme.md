

<p align="center">
  <h3 align="center">How to access a particular port in GCP</h3>

  <p align="center">
    <br />
    <br />
    <br />
    <a href="https://youtu.be/TiH9s4YM-aQ">View Tutorial</a>
  </p>
</p>






<!-- GETTING STARTED -->
## Getting Started

To configure TCP data input in Splunk follow these simple steps.

### Opening or Accessing a port

1. There are two ways to do it.If you have a instance up and running Click on the instance name and scroll down and Click Network
  
  
2. Choose firewall rule
   
   
3. Type port number 514 and Click next 
  
  
4. Choose Searching and Reporting App  
   
   
5. Creating a new index,sourcetype are optional


6. Review and Click Sumbit


  **Note** - Always remember to create the firewall rule to access the port


7. In the non splunk instance execute the following command to send the data to splunk
   ```sh
   cat <location of file> | nc <IP address> <Port number>
   ```

<!-- USAGE EXAMPLES -->
## More Details

Use the below link for the official documentation of Splunk

 please refer to the [Documentation](https://docs.splunk.com/Documentation/SplunkCloud/latest/Data/Monitornetworkports)





