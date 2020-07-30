# Transform-Object

## Getting Started
The transform feature lets you perform various operations on the input data in order to help you customize your workflow output or the data you send to the next action. This feature is available in all actions supported by webMethods.io Integration. 
Following instructions will get you a copy of the specific Date transform in your webMethods.io Integration tanent.
List of Date transform available in the webMethods.io Integration are:
1. <b> Contains Key : </b>This operation lets you check whether the specified key is present in the given object.
2. <b> Create Object: </b>This operation lets you create an object containing specific key-value pairs.
3. <b> Get: </b>This operation will fetch the value of a key..
4. <b> List Keys:</b> This operation lets you fetch the keys of the specified object.
5. <b> Put:</b> This operation lets you insert a key-value pair in the specified object.
6. <b> Remove: </b>This operation lets you remove an item from the given object.
7. <b> Size:</b> This operation lets you get the size of the given object.

### Prerequisites
1. An account in [webmethod.io](https://www.softwareag.cloud/site/product/webmethods-io-integration.html) with webMethods.io Integration access.

### Importing the recipie to your webMethods.io Integration tanent:
1. Download the specific zip file which transform you want test, from this github page.
2. Log in to your webmethod.io account then go to `webMethods.io Integration`.
3. Select `Reciepes` the click on `Import`.
![image](https://user-images.githubusercontent.com/60179170/88805095-5d798500-d1cc-11ea-97de-dec146247ecc.png)
4. Then select the downloaded file and click on `open`.
![image](https://user-images.githubusercontent.com/60179170/88961817-2b971a00-d2c3-11ea-881f-2df53ac0a1ec.png)
5. After that you will be able the workflow in your recipie list.<br/>
![image](https://user-images.githubusercontent.com/60179170/88919083-236db900-d288-11ea-8748-0df58c9ef64f.png)
6. Click on that workflow and then select the project name where you want to import the workflow and click on `Done`.
![image](https://user-images.githubusercontent.com/60179170/88805882-5737d880-d1cd-11ea-8414-17324e86dcd6.png)
7. After that you will see a short description about that transform along with the workflow name. Click on `Import` here.
![image](https://user-images.githubusercontent.com/60179170/88919169-48622c00-d288-11ea-9e65-ba84509c675b.png)
Yeee now you have succesfully imported the work flow.

### Run the workflow:
1. Go to that specific project where you have imported the workflow. Hover over the workflow that you have imported and click on `edit`.
![image](https://user-images.githubusercontent.com/60179170/88919441-b9094880-d288-11ea-9295-9e8a5414b9f3.png)
2. Click on the `edit` icon present in the top left corner.
![image](https://user-images.githubusercontent.com/60179170/88808530-a29fb600-d1d0-11ea-90e1-d4efeebfe853.png).
3. Now go to the workflow description and coppy the requested body. `only the JSON part`. And click `Done`. <b> If There is no request body present you can dirctly run the workflow (Step 8).</b>
![image](https://user-images.githubusercontent.com/60179170/88919785-5c5a5d80-d289-11ea-9408-f970bf04f165.png)
4. Now `double click` on the start .
![image](https://user-images.githubusercontent.com/60179170/88809305-9700bf00-d1d1-11ea-91a2-235dfaf46578.png).
5. From the list click on webhook.<br/>
![image](https://user-images.githubusercontent.com/60179170/88810663-49855180-d1d3-11ea-914e-09f501278c2f.png)
6. Click `Next`.<br/>
![image](https://user-images.githubusercontent.com/60179170/88910377-05995780-d27a-11ea-99cc-b472dac0f0ef.png)
7. Now paste the coppied data in to the body and click `Next` and then `Done`.
![image](https://user-images.githubusercontent.com/60179170/88919905-8744b180-d289-11ea-9c8d-a3ba8a61d192.png)
8. Now run the workflow it will give you output in the logger. Here you can see the Difference betwwen the dates.<br/>
![image](https://user-images.githubusercontent.com/60179170/88919992-ad6a5180-d289-11ea-94c6-8ffa9806f743.png)

### Test With other input:
1. Open the weebhook and change the data inside the body. <b> Donot change the key value and the formte of the data. ie. "data1", "data2" and "data3" is key here and Match the date formate with the "data3" formate. If you change the "data3" provide the inpute in that format </b>.<br/>
![image](https://user-images.githubusercontent.com/60179170/88920617-c58ea080-d28a-11ea-92d3-fa83abeb4bf4.png)
2.  Now run the workflow it will give you output in the logger. 

