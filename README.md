# MAD_practical6_21012011002

AIM: What is Service? Write down types of Service. Create an MP3 player application by using service by following below instructions.


answer : service is a component that performs background tasks without a user interface. Services are used to execute long-running operations independently of the user interface, making them suitable for tasks like playing music in the background, downloading files, or handling network requests. Services run in the background and do not interact directly with the user.
this are types of services 


1)Foreground Service : Services that notify the user about its ongoing operations are termed as Foreground Services. Users can interact with the service by the notifications provided about the ongoing task. Such as in downloading a file, the user can keep track of the progress in downloading and can also pause and resume the process.

2)Background Service :- Background services do not require any user intervention. These services do not notify the user about ongoing background tasks and users also cannot access them. The process like schedule syncing of data or storing of data fall under this service.

3)Bound service : This type of android service allows the components of the application like activity to bound themselves with it. Bound services perform their task as long as any application component is bound to it. More than one component is allowed to bind themselves with a service at a time. In order to bind an application component with a service bindService() method is used.

1) Create MainActivity and design according to shown in below image. 

2) Create Service Class and implement MediaPlayer Object

![image](https://github.com/Chintan0484/MAD_practical6_21012011002/assets/98694412/dd30fc81-e06f-4bdd-b824-64f17562bffd)

![image](https://github.com/Chintan0484/MAD_practical6_21012011002/assets/98694412/c9513b3d-3cab-4157-bd70-f3953c78e199)




