Module-3 : Designing-APIs

1)Walkthrough 3-1: Use API Designer to define an API with RAML

In Design Center , I have created new project named Demo_project .

It contains "/accounts" GET and POST method .

![image](https://user-images.githubusercontent.com/70746268/120444088-ec36cf80-c3a4-11eb-916f-6c0f8393c248.png)

2)Walkthrough 3-2: Use the mocking service to test an API

GET

![image](https://user-images.githubusercontent.com/70746268/120444354-2d2ee400-c3a5-11eb-9e9a-172a7f7dd1a6.png)

![image](https://user-images.githubusercontent.com/70746268/120444426-3ae46980-c3a5-11eb-9ccb-926c751618f5.png)

![image](https://user-images.githubusercontent.com/70746268/120444453-420b7780-c3a5-11eb-8793-d7cf5505a814.png)

![image](https://user-images.githubusercontent.com/70746268/120444472-48015880-c3a5-11eb-8f24-3a3adbbd5267.png)

POST

![image](https://user-images.githubusercontent.com/70746268/120444558-5b142880-c3a5-11eb-80a1-23db326ba3c2.png)

![image](https://user-images.githubusercontent.com/70746268/120444627-6c5d3500-c3a5-11eb-8557-69a8d60c4f4c.png)

3)Walkthrough 3-3: Add request and response details

Next ,I have created a new folder datatypes , In datatypes , I have created acc.raml which contains the response data type that contain the following fields: id, firstName, lastName, address, postal, country, miles, creationDate, and type. The creationDate field is of type datetime and miles is of type integer.

![image](https://user-images.githubusercontent.com/70746268/120445154-f907f300-c3a5-11eb-9b55-1757daf5d472.png)

Next ,I have created a new folder examples , In examples , I have created ACCexample.raml which contains the GET data of the account holders .

![image](https://user-images.githubusercontent.com/70746268/120445262-1046e080-c3a6-11eb-9b3a-d4220b44241c.png)

![image](https://user-images.githubusercontent.com/70746268/120445338-22c11a00-c3a6-11eb-9fdc-edd199876d09.png)

Now ,in the same folder examples , I have created another file ACCNoID.raml which contains POST data .

![image](https://user-images.githubusercontent.com/70746268/120445417-38364400-c3a6-11eb-908c-86d6ce5762b1.png)

Datatypes in raml file

![image](https://user-images.githubusercontent.com/70746268/120445808-9d8a3500-c3a6-11eb-9666-a8064bac5fc4.png)

Request and response for GET

![image](https://user-images.githubusercontent.com/70746268/120446032-d3c7b480-c3a6-11eb-88fc-b94afa069d3a.png)

Request and response for POST

![image](https://user-images.githubusercontent.com/70746268/120446236-fb1e8180-c3a6-11eb-9b15-b2874ad7f73c.png)

4)Walkthrough3-4: Add an API to Anypoint Exchange

![image](https://user-images.githubusercontent.com/70746268/120446437-2e611080-c3a7-11eb-951a-4754c369a080.png)

![image](https://user-images.githubusercontent.com/70746268/120446605-55b7dd80-c3a7-11eb-922d-e832addf083b.png)

Editing and again pubishing to excahange...

![image](https://user-images.githubusercontent.com/70746268/120446850-93b50180-c3a7-11eb-8050-e2d752ee4420.png)

After publishing,

![image](https://user-images.githubusercontent.com/70746268/120447061-d24abc00-c3a7-11eb-8663-d26701fe5bc6.png)

5)Walkthrough 3-5: Share an API

Share an API within anorganization using theprivate Exchange

![image](https://user-images.githubusercontent.com/70746268/120447689-76ccfe00-c3a8-11eb-8c66-4a29111898df.png)

Publishing it in public portal,

![image](https://user-images.githubusercontent.com/70746268/120447829-995f1700-c3a8-11eb-92bc-9cf5ef6383af.png)




