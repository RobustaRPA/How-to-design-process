# Introduction to process design with Robusta RPA

* ### You can log into Modeler (Design Studio) by clicking on the link below. Use the same username and password used to connect Robusta orchestrator.
### https://178.18.207.85:8443/modeler/

![image](https://user-images.githubusercontent.com/87966919/130034214-f82e8e38-e7e7-43bc-a2d5-1257a724db0e.png)

* ### In Processes tab, you will find the menus to create, import, search and edit processes.

![image](https://user-images.githubusercontent.com/87966919/130034243-65d51c0d-62f2-4081-a869-51789cdca7f0.png)
* ### To create a process, you need to click Create Process button, fill necessary fields and then, click Create New Model button.

![image](https://user-images.githubusercontent.com/87966919/130034253-f4eb1687-7cfb-4fe1-a38d-df9a676f9481.png)

* ### The following screenshot shows process design studio. On the left pane, you see BPM and RPA components all together. On the right side, you see the canvas where we generate process flow. 

![image](https://user-images.githubusercontent.com/87966919/130034276-d89ff180-56cb-4c71-bb00-fa555a06447c.png)

* ### You just need to drag and drop a selected activity onto the canvas and fill necessary parameters. To define the flow, you need to connect the activities to each other by using arrows.

* ### For example, the values for Move activity under ‘File operations’ may be set as given at the following table:
| Columns  | Inputs |
| ------------- | ------------- |
|File name|	C:\TrainingProcesses\MoveFile\File to Move.txt|
|Destination path|	C:\TrainingProcesses\MoveFile\Folder to Move\File to Move New.txt|

![image](https://user-images.githubusercontent.com/87966919/130034332-e6b1fbcb-6ba6-49d7-8f4a-23aba18ecaba.png)

![image](https://user-images.githubusercontent.com/87966919/130034351-3747c182-0c18-4e85-ba58-ed0d95077ffd.png)
* ### After you completed the process flow, validate the model by clicking validate (![image](https://user-images.githubusercontent.com/87966919/130036145-964ddf78-cd11-4b75-9797-6b73926fa24e.png))  button. 
![image](https://user-images.githubusercontent.com/87966919/130034362-6cb04634-fd27-48da-a64d-e8044e1ef489.png)
* ### After you validated the process flow, save the model by clicking save ( ![image](https://user-images.githubusercontent.com/87966919/130034390-5c30a0f9-028a-408d-b099-056254352df1.png) ) button. 


![image](https://user-images.githubusercontent.com/87966919/130034405-31e38920-c632-4787-a47a-8c49ccae8edf.png)

* ### After saving a process, this process should be included in an App to be run. In Apps tab, you will find the menus to create, import, edit apps.

![image](https://user-images.githubusercontent.com/87966919/130034420-f18b0c2a-8e3c-466b-adda-3d7401fa0648.png)

* ### To create a App, you need to click Create App button, fill necessary fields and then, click Create New App Definition button.
![image](https://user-images.githubusercontent.com/87966919/130034454-19e06615-0681-4016-82f9-d4d463eb4618.png)
* ### Set Group access as ‘Your Group Id’ to prevent your app to be seen by other groups.

![image](https://user-images.githubusercontent.com/87966919/130034484-5b675ec1-247a-4f89-b29c-8292d8fcc3da.png)

* ### Click ‘Edit included models’ button and select the process to be included in your app. Then, click any space out of popup window to close it.

![image](https://user-images.githubusercontent.com/87966919/130034510-b873509e-bf33-4427-b093-778e2edf8a23.png)


* ### Save the app by clicking save (![image](https://user-images.githubusercontent.com/87966919/130034532-410cc1ef-d056-4262-a174-20dbc3f255b1.png)) button. 

![image](https://user-images.githubusercontent.com/87966919/130034548-98b64ed5-03c4-4305-9604-2e7d766fee36.png)

* ### To run the process, go back to Processes tab and select your process.

![image](https://user-images.githubusercontent.com/87966919/130034580-a9d08605-f61e-44e4-b20b-405b67929de3.png)

* ### To run the process on a worker, click play (![image](https://user-images.githubusercontent.com/87966919/130034596-c78e54b4-50cf-4b4d-9edb-e5eb8df80209.png)) button.


![image](https://user-images.githubusercontent.com/87966919/130034613-295b6a04-c5a8-4712-b04e-a0073beede89.png)


* ### Select your app and your worker on the popup screen. Theni click Run Process button. One you see ‘Process Successfully scheduled’ message on the screen, your process is scheduled to be picked by Scheduler to be sent to your worker.

![image](https://user-images.githubusercontent.com/87966919/130034633-a36005d8-9e55-4cbf-b252-bc21167c4f3f.png)

# Monitor Scheduled Processes with Robusta Scheduler

* ### You can open Scheduler module by clicking on the link below. Then, select your app to monitor scheduled processes in this app.

* ### https://178.18.207.85:8443/scheduler/

![image](https://user-images.githubusercontent.com/87966919/130034700-d0676c33-16c3-4a7b-bcd3-0462ad3b0380.png)

In the Scheduled Processes tab, you can search and check statuses of the scheduled processes. 
![image](https://user-images.githubusercontent.com/87966919/130034732-95436a38-6074-4fe0-a928-15e59c3f5e09.png)

* ### By clicking Instances icon on a row, you can go to the instance of a scheduled process to see run details.  

![image](https://user-images.githubusercontent.com/87966919/130034757-1a49cac6-3df3-493e-86d1-1bf5b02272c9.png)
* ### When you click Show Diagram icon on a row, the flow diagram is shown, and the path followed is seen in blue. Also, the values of the variables defined in the process is available at this page.	

![image](https://user-images.githubusercontent.com/87966919/130034772-34ed5277-c4d1-49a6-a2c1-d677dfa58cfd.png)



