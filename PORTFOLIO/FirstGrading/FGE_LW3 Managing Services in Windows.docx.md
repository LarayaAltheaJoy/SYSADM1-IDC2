

<img width="790" alt="image" src="https://github.com/user-attachments/assets/106f56f2-d98a-435d-91de-568168129b59">


1. # SYSADM1 – Managing Services in Windows

2. # Requirement: 

* A virtual machine running Linux and Windows OS


  **Services** are background processes that run independently of user interactions in Windows. They provide essential system functions, such as network connectivity, printing, and time synchronization. This lab will guide you through the process of managing services using the Services app.

# Instructions: 

1. Open the Start menu and search for "Services"

2. Familiarize yourself with the columns, including Service Name, Display Name, Status, and Startup type.

3. Right-click on a service and select "Start", "Stop", or "Restart". Fill out the table below

   **WINDOWS 10**

<img width="790" alt="image" src="https://github.com/user-attachments/assets/1b5d21f0-0cc9-493d-9995-c3fdd2badca5">
<img width="790" alt="image" src="https://github.com/user-attachments/assets/f1d9af3c-5f5c-4e14-8a2b-a1d7db3185e3">


4. Select five network services, right-click to view its properties. Modify the startup setting to Manual.

   **SS**:

<img width="790" alt="image" src="https://github.com/user-attachments/assets/fa9f6a06-1a26-483d-8baf-a0e08ba6e0f2">
<img width="790" alt="image" src="https://github.com/user-attachments/assets/51e932ba-7d1b-4a25-962e-6a3b54141ffc">

5. Explore the "General", "Recovery", and "Log On" tabs to understand additional service settings.

6. Create a batch file that will be added as a new service later on. Refer to the batch file code below.

<img width="528" alt="image" src="https://github.com/user-attachments/assets/1f487d7e-0948-4a88-892d-0e2025632a80">

7. Save the batch file in Z:\\lastname\_timer.bat

8. Use the sc command to add timer.bat service in the command line interface.

   *sc create BatchTimerService binPath= "path\_to\_your\_batch\_file.bat" start= auto*

*net start BatchTimerService*

**Replace path\_to\_your\_batch\_file.bat with the actual path to your batch file.**

9. Verify that BatchTimerService has been added to the services.

   **SS:** 

<img width="528" alt="image" src="https://github.com/user-attachments/assets/a4443d24-f802-46c5-8b1e-3afa9037da68">


   

10. **Testing the Service:** Now, if you open a new command prompt, you should see the timer countdown without requiring your interaction. Once the timer finishes, you'll see the "Timer finished\!" message.

    **SS:**

<img width="528" alt="image" src="https://github.com/user-attachments/assets/cb3d9dba-7b1c-4c50-9b21-94f369f7384f">

<img width="623" alt="image" src="https://github.com/user-attachments/assets/aa69451d-f739-43ae-b3e6-9041a2dc48d1">
