

<h1>Network File Shares and Permissions</h1>
This tutorial outlines how to give network files permissions and how to share them.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- File Explorer 

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Steps</h2>

- Create folder
- Set Permissions (Share the folder)
- Attempt to access file sharing 


<h2> Steps</h2>

<p>
<img width="981" height="500" alt="image" src="https://github.com/user-attachments/assets/510b0140-d096-44be-82a3-54f64ee0f163" />

</p>
<p>
Connect into virtual machine and create three folders. Name the folder “read-access”, “write-access”, “no-access”.
</p>
<br />

<p>
<img width="1192" height="587" alt="image" src="https://github.com/user-attachments/assets/3b4ac28c-6af0-41d1-af68-5c10b335f87b" />
<img width="1220" height="592" alt="image" src="https://github.com/user-attachments/assets/87096da4-84f9-4470-ae2a-54b13643fb04" />
<img width="1190" height="587" alt="image" src="https://github.com/user-attachments/assets/4f6663ac-edf0-429b-9694-5fd52ed15a61" />



</p>
<p>
<h2>Set the following permissions (share the folder)</h2>

- Folder: “read-access”, Group: “Domain Users”, Permission: “Read”
- Folder: “write-access”,  Group: “Domain Users”, Permissions: “Read/Write”
- Folder: “no-access”, Group: “Domain Admins”, “Permissions: “Read/Write”
</p>
<br />

<p>

</p>
<p>
Connect to a different virtual machine and attempt to access file shares as a normal user. Try to access the folders you just created. Which folders can you access? Which folders can you create stuff in?
</p>
<br />
