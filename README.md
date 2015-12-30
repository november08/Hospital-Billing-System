To open a port in the Windows firewall for TCP access 

1. On the Start menu, click Run, type WF.msc, and then click OK. 
2. In the Windows Firewall with Advanced Security, in the left pane, right-click Inbound Rules, and then click New Rule in the action pane (upper right corner). 
3. In the Rule Type dialog box, select Port, and then click Next. 
4. In the Protocol and Ports dialog box, select TCP. Select Specific local ports, and then type the port number of the instance of the Database Engine, In my case we are using the default which is 1433. Click Next. 
5. In the Action dialog box, select Allow the connection, and then click Next. 
6. In the Profile dialog box, I am going to Leave Domain turned on and turn private and public off. Then click Next. 
7. In the Name dialog box, type "Allow SQL 1433 Inbound” and for a description I am putting in the same. Then click Finish.

From: http://blogs.technet.com/b/danstolts/archive/2011/06/08/how-to-open-firewall-port-1433-for-sql-server-database-engine-for-use-with-scom-or-anything-else.aspx

# Hospital-Billing-Syste
