# Creating Load Balancer

1. Open the navigation menu and click **Networking** &rarr; **Load Balancer**
![drawing](./SS/lb/1.png)

2. Click on **Create Load Balancer**

3. Fill the name of load balancer, select "Public" and "Ephemeral"

     ![drawing](./SS/lb/2.png)

4. Leave shape settings as default.

    ![drawing](./SS/lb/3.png)

5. Choose the network you created in before.

     ![drawing](./SS/lb/4.png)

6. Click "Next" at the bottom.

7. Leave backends empty for now

    ![drawing](./SS/lb/6.png)

8. Set the port to "5000".

    ![drawing](./SS/lb/8.png)

9. Click "Next" at the bottom.

10. Select "HTTP" and specify the port as "80".

    ![drawing](./SS/lb/10.png)

11. Disable the "error log"

    ![drawing](./SS/lb/11.png)

12. Click "Submit" at the bottom.

Now you have created you first LB.

After the server will be ready we will connect backends to it.
