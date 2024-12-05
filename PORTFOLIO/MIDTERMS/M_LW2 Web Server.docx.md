<img width="686" alt="image" src="https://github.com/user-attachments/assets/273d98be-6f6c-4843-b56f-6d8e4f826279">

# SYSADM1 – Setting Up Webserver

# Requirement: 

* A virtual machine running Linux and Windows OS

  Task Instructions:

1. Install IIS by adding it as a role, select necessary features, include monitoring tools

<img width="639" alt="image" src="https://github.com/user-attachments/assets/f972361f-8d84-49bf-bdf8-f35f7563cd02">


2. Create a website by opening IIS Manager 

   * Right-click on the server’s name and select Internet Information Services Manager.

   * Right-click on Sites and select Add Website.

   * Enter a name, description, physical path (where your website files will reside), IP address, port, and host name.

<img width="449" alt="image" src="https://github.com/user-attachments/assets/57c709a0-a4b6-4cc8-ac10-9c7183c58002">


   (*hostname should be the registered domain name)*

   

3. Configure the Website:

   * Right-click on your website and select Edit.

   * Set the Default Document to the name of your main HTML file \>default.html

   * Configure other settings as needed (e.g., SSL certificates, authentication)

<img width="449" alt="image" src="https://github.com/user-attachments/assets/12d33e94-fb32-4eec-b16c-2df3e01a0e3e">

4. Create a Web Page:

   * Create an HTML file in the physical path you specified.

<img width="413" alt="image" src="https://github.com/user-attachments/assets/fef63f4e-5144-4256-aa17-1286a85c2262">

   * Save it as default.html or your preferred name.

<img width="442" alt="image" src="https://github.com/user-attachments/assets/2b01fdff-3b43-4d9f-bdbc-25d99da4f115">

5. Test the Web Server:

   * Open a web browser and enter the URL of your website (e.g., http://localhost).

   * You should see your web page displayed.

<img width="552" alt="image" src="https://github.com/user-attachments/assets/0488a07d-5b9f-4f62-bd6e-cd9d7feefd91">

 


Grading Rubric

| Criteria | Points | Description |
| :---- | :---- | :---- |
| Web Server Installation | 15 | Correctly installs IIS or another web server on the virtual machine. |
| Website Configuration | 15 | Successfully configures the website with the correct physical path, IP address, port, and default document. |
| Successful Access | 15 | Successfully accesses the web page from the client computer using the correct URL. |
| Troubleshooting | 15 | Demonstrates ability to troubleshoot common issues, such as network connectivity problems or configuration errors. |
| Documentation | 10 | Provides clear and concise documentation of the installation, configuration, and testing process. |
| Total | /70 |  |


