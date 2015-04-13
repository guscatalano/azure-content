Get the same O365 Experience on any device
===================


This article will cover how to deploy Office 365 on any device in your company. Your users can get the same capabilities and UI experience on Android, Apple and Windows. We will accomplish this using Azure RemoteApp by hosting Office 365 on scale-able Virtual Machines in Azure that users can connect to. This set of virtual machines we call a "Cloud Collection". 

----------


Create a Cloud Collection
-------------
First after you have created an Azure Account, navigate to "RemoteApp" by clicking on the link on the left side. 
![Showing Azure RemoteApp on the Azure Portal](http://i.imgur.com/G2XzS3m.jpg)

Then continue by clicking new on the bottom and "quick creating" a collection. Provide a name, the region, the subscription, the plan and the image "Office Proffesional 2013" that we provide.
![Create Dialog](http://i.imgur.com/8YGwuq6.png)

Once you finish the form the collection creation process should start. This may take up to an hour or so.

![Waiting](http://i.imgur.com/OsALu9E.png)

Once the process is done, it will look something like this. If we click on "Publishing" we can see that most Office applications have been published for us already.
![Collection created](http://imgur.com/aGObNwR.png)

![Published apps](http://i.imgur.com/anmHb01.png)

At this point you can also add more users that have access to this collection by clicking "User Access"
![Configure user access](http://i.imgur.com/QKE2TVh.png)

Now let's try out connecting to Office 365!

Connecting to Office 365
-------------
We'll head over to https://www.remoteapp.windowsazure.com/ and click on "install client" to install the Azure RemoteApp client on the device you're on. The screenshots below are for windows.

Once the application starts you'll be asked to sign in with your live ID, use the same one as your Azure account for now. When you're signed in you should see a notification about new invitations, click there and you should see a list like one below, accept the invitation that matches your Azure account owner email. 

![New invitation](http://i.imgur.com/R781pz4.png)

What it looks like when there are new invitations.

![Accept an application](http://i.imgur.com/g9ggPwH.png) 

Once you accept the invitation you should see all the office apps in the Azure RemoteApp client.

![List of apps](http://i.imgur.com/U7KQrGS.png)

When you click on any of these the application should start on the Azure Virtual Machine and you should be all set! Enjoy!

![powerpoint](http://i.imgur.com/96CcWVB.png)
