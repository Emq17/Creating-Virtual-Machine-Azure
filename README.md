<p align="center">
<img src="https://i.imgur.com/0K5FxAa.png" alt="Logo"/>
</p>

# Establishing Virtual Machines With Remote Desktop

This outlines the steps using Microsoft Azure to create Virtual Machines & having Microsoft Remote Desktop to deploy connection. 

<h2>Environments and Technologies</h2>

- Microsoft Azure
- Microsoft Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)

<h2>List of Prerequisites</h2>

- Subscription of Microsoft Azure

<h2>Tutorial Steps</h2>

>**Note***
>_While creating a Virtual Machine, a Resource Group will automatically be created as well. Knowing how to create a VM should provide a solid base to mess around with future projects._

- Go inside the Virtual Machine portal by searching it up in the search tab.
  
![Screen Shot 2023-12-16 at 7 43 49 PM](https://github.com/Emq17/Observing-IP-Addresses-Through-ProtonVPN/assets/147126755/52632ac6-a309-4eaa-adcd-ba6227546957)

- Then choose "Azure Virtual Machine" under the "Create" tab.

![Screen Shot 2023-12-16 at 7 48 27 PM](https://github.com/Emq17/Observing-IP-Addresses-Through-ProtonVPN/assets/147126755/be2f6106-32be-46bc-a04f-7df430a1acfb)

- Start by creating a name for your VM and choosing another geographic location ("Region"). I had randomly set mine to "(Africa) South Africa".
- Also choose the operating system "Windows 10 Pro, version 22H2" for your "Image."

![Screen Shot 2023-12-16 at 7 59 41 PM](https://github.com/Emq17/Observing-IP-Addresses-Through-ProtonVPN/assets/147126755/37c70a45-3ddd-4031-8eab-129b1d6624bf)
     
- Scroll down a bit and choose your preferred size.
- After that, go ahead and create a Username/Password to be able to log in to your Virtual Machine. Leave everything else as is.
- Click the box to confirm licensing then hit "Review + create."

![Screen Shot 2023-12-16 at 8 08 55 PM](https://github.com/Emq17/Observing-IP-Addresses-Through-ProtonVPN/assets/147126755/0bcc5f47-4fd4-4a11-8bd9-08ce7a258cdb)

- After your VM passes validation, click create.

![Screen Shot 2023-12-16 at 8 21 59 PM](https://github.com/Emq17/Observing-IP-Addresses-Through-ProtonVPN/assets/147126755/193c2084-6782-4e9b-8c76-81c6a30b8acb)

- For this step I ended up using the "Microsoft Remote Desktop" application on my Macbook. You can download this free through the app store.

![Screen Shot 2023-12-16 at 8 28 54 PM](https://github.com/Emq17/Observing-IP-Addresses-Through-ProtonVPN/assets/147126755/27ff32a7-b4ee-4e21-9973-3430b246b1f6)

- Grab the public IP Address within your VM inside Azure and use that as your PC name. 

![Screen Shot 2023-12-16 at 8 32 40 PM](https://github.com/Emq17/Observing-IP-Addresses-Through-ProtonVPN/assets/147126755/f33fe4dc-8581-44c1-8831-081f5ab599d2)

- Once added you will simply use your log in credentials that you created while setting up your VM.

![Screen Shot 2023-12-16 at 8 34 04 PM](https://github.com/Emq17/Observing-IP-Addresses-Through-ProtonVPN/assets/147126755/a6e3065f-0d7b-4090-a24a-8e6be650f177)

- Congratulations. You should be logged into the Windows platform now.

![Screen Shot 2023-12-22 at 6 39 20 PM](https://github.com/Emq17/Establishing-Virtual-Machines-With-Remote-Desktop/assets/147126755/b6ac51c3-53f8-4266-a089-d8a89e38e23f)


