<p align="center">
<img src="https://www.imagar.com/wp-content/uploads/2018/06/azure.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>How to Setup a Subscription and a Resource in Azure</h1>
This is online tutorial on how to setup an subscription and resources in Azure. Creating a resources in Azure will allow beginners to practice and learn how to use Azure through labs to gain experience with the application.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Steps</h2>

 -Step 1: Create an Azure account and open the Azure portal
 
 -Step 2: Create a Resource group within the Azure portal
 
 -Step 3: Create a storage account within the resource group created
 
 -Step 4: Create a file on your desktop and upload it into the storage account
 
 -Step 5: Edit the file created in the last step within the portal
 
 -Step 6: Download file and observe the changes made
 
 -Step 7: Delete the resource group so that you do not incur charges
 
 -Step 8: Verify that the resource is deleted


<h2>Azure Setup Steps and Resource Group Creation</h2>

<p>
<img src="https://i.imgur.com/ZVBPCGk.png"/>
</p>
<p>
First, you will need to create an Azure account. Go to https://azure.microsoft.com/en-us/free/ and click the green start free button. This step will require a credit/debit card, but it will not be charged.
</p>
<br />

<p>
<img src="https://i.imgur.com/7f3nlwW.png"/>
</p>
<p>
After the account is made, you will need to go to https://portal.azure.com. From here, you will sign into the portal with the email and password that you created in the previous step. Inside the portal you will type "Subscriptions' and click the gold key to ensure that your subscription is currently active. After this, we will create a resource group.
</p>
<br />

<p>
<img src="https://i.imgur.com/bhgaF6z.png"/>
</p>
<p>
Navigate to resource groups by typing it into the search bar. From there press the blue button that says "Create resource group".
</p>
<br />

<p>
<img src="https://i.imgur.com/mKOYrIm.png"/>
</p>
<p>
We will finally start configuring our resource group. You will most likely only have one subscription so it will already be defaulted onto the one you have created. We will only be creating the name and changing the region. For the name of the group, we can name it "RG-1". You can change this to whatever you would like, but this is the sample name we will be using. Next, you will set the region to whatever is closest to you by pressing the dropdown menu. We will be using "West US 3" for this tutorial. Press "Next: Tags >" on the bottom left after you have finished.
</p>
<br />

<p>
<img src="https://i.imgur.com/eFktQsX.png"/>
</p>
<p>
On this page you can assign tags to the resource group. Skip this as you don't have to assign any tags, but this is just for organizations to keep track of data pertaining to certain resources. Hit the "Next : Review + create >" button. 
</p>
<br />

<p>
<img src="https://i.imgur.com/dVpUMK1.png"/>
</p>
<p>
This last page will be where you confirm everything is correct and press "Create" on the bottom left to finalize the creation of the resource group.
</p>
<br />

<p>
<img src="https://i.imgur.com/Qw9ntW7.png"/>
</p>
<p>
We will now check to see if the resource group that we created is active by going back to the Resource Group page by typing it into the search bar once again. Next we will be testing the resource group by creating a Azure Storage Account which is like a Google Drive or iCloud for apple.
</p>
<br />

<p>
<img src="https://i.imgur.com/Cbd7gtY.png"/>
</p>
<p>
Create a storage account by typing "Storage Account" in the search bar and pressing the button in the service section. Once there, press the "Create storage account" button.
</p>
<br />

<p>
<img src="https://i.imgur.com/Jv1Znq8.png"/>
</p>
<p>
Next we will make sure the subscription and resource group is selected to the one we just created. If not, select it by pressing the drop down menu for both. From there, you'll need to make a unique name for the account and confirm that the account is in the same region as your resource group. You will then hit the blue review button on the bottom left to run the validation. Lastly, you will hit create. 
</p>
<br />

<p>
<img src="https://imgur.com/bQPFBBf.png"/>
</p>
<p>
Wait for it to complete deployment and hit "Go to resource".
</p>
<br />

<p>
<img src="https://imgur.com/BHbAhHg.png"/>
</p>
<p>
Once you are in the storage account, click on containers.
</p>
<br />

<p>
<img src="https://imgur.com/CMQKtQu.png"/>
</p>
<p>
Now create a new container, name it, and hit create.
</p>
<br />

<p>
<img src="https://imgur.com/3pl9aY3.png"/>
</p>
<p>
Now click on the new container you just made, and we are going to upload a basic text file into the container.
</p>
<br />

<p>
<img src="https://imgur.com/w7sOZVz.png"/>
</p>
<p>
Just make a new text document on your desktop, then name it and write what ever you want in it.
</p>
<br />

<p>
<img src="https://i.imgur.com/1nutBNY.png"/>
</p>
<p>
Click the upload button and you can just drag and drop the file from your desktop or you can search for it in file explorer, and then upload it!
</p>
<br />

<p>
<img src="https://i.imgur.com/TIOrw9I.png"/>
</p>
<p>
Now that you have uploaded the file, you can edit, download it to your computer, or do whatever you want with it.
</p>
<br />

<p>
</p>
<p>
That is the last step of creating a storage account. Now we will delete the resource group to make sure you don't incur a charge. Once deleted you will need to remake the resource group, but you can do this as many times as you like to practice.
</p>
<br />

<p>
<img src="https://i.imgur.com/TZXjAuP.png"/>
</p>
<p>
To delete the resource group, just go back to the resource groups page, click on the resource group, click delete resource group, and type/copy paste the resource group's name to confirm, and then click delete.
