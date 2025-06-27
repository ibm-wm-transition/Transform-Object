# Transform-Object

## Getting Started
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
![image](https://user-images.githubusercontent.com/60179170/88961926-52ede700-d2c3-11ea-8e43-957edd7a0db5.png)
Yeee now you have succesfully imported the work flow.

### Run the workflow:
1. Go to that specific project where you have imported the workflow. Hover over the workflow that you have imported and click on `edit`.
![image](https://user-images.githubusercontent.com/60179170/88961999-6dc05b80-d2c3-11ea-8f9c-662d05e820c7.png)
2. Click on the `edit` icon present in the top left corner.
![image](https://user-images.githubusercontent.com/60179170/88808530-a29fb600-d1d0-11ea-90e1-d4efeebfe853.png).
3. Now go to the workflow description and coppy the requested body. `only the JSON part`. And click `Done`. <b> If There is no request body present you can dirctly run the workflow (Step 8).</b>
![image](https://user-images.githubusercontent.com/60179170/88962061-83ce1c00-d2c3-11ea-899b-667de76e0b3d.png)
4. Now `double click` on the start .
![image](https://user-images.githubusercontent.com/60179170/88809305-9700bf00-d1d1-11ea-91a2-235dfaf46578.png).
5. From the list click on webhook.<br/>
![image](https://user-images.githubusercontent.com/60179170/88810663-49855180-d1d3-11ea-914e-09f501278c2f.png)
6. Click `Next`.<br/>
![image](https://user-images.githubusercontent.com/60179170/88910377-05995780-d27a-11ea-99cc-b472dac0f0ef.png)
7. Now paste the coppied data in to the body and click `Next` and then `Done`.
![image](https://user-images.githubusercontent.com/60179170/88962322-e6bfb300-d2c3-11ea-94a2-98e986778d98.png)
8. Now run the workflow it will give you output in the logger. Here you can see the size of the provided Object.<br/>
![image](https://user-images.githubusercontent.com/60179170/88962397-02c35480-d2c4-11ea-8384-a5fcf12de7d7.png)

### Test With other input:
1. Open the weebhook and change the data inside the body. <b> Donot change  the formte of the data. ie. the date formate is object </b>.<br/>
![image](https://user-images.githubusercontent.com/60179170/88962560-3aca9780-d2c4-11ea-8f76-a92f35ef37e2.png)
2.  Now run the workflow it will give you output in the logger. 

--------
These tools are provided as-is and without warranty or support. They do not constitute part of the webMethods product suite. Users are free to use, fork and modify them, subject to the license agreement. While we welcome contributions, we cannot guarantee to include every contribution in the master project.
