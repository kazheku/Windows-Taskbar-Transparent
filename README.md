<h1> ¡Windows-Taskbar-Transparent! </h1>


## 📃 Presentation

Hi guys, I'm going to cut to the chase,  I bring you a tutorial to make the taskbar invisible  🟢**without programs**🟢

### How does this work?

Well, this method is performed through regedit. 

⚠ **Don't worry about reading regedit, it may cause you concern or fear of creating a problem in your system, but this method is very simple and intuitive to do.**


## ✏ Explanation 

📌 **I am going to explain it step by step, so that there are no problems when changing our taskbar.**

🔵 We go to our system configuration, once there we go to customization. Once inside, we activate the following option:

![1Sin título](https://user-images.githubusercontent.com/115459058/223187711-f377437b-a6cb-4b23-b9ce-d153d8c62722.png)

🔸 This option must be enabled, otherwise this method will not work.

---

🔵 The next step is to go to regedit, how to do it?
 
 🔹 Press the Windows key + r
 
 🔹 Type regedit 
 
 🔹 Click on accept
 
 ![2Sin título](https://user-images.githubusercontent.com/115459058/223189680-21922683-2108-4068-b0b8-fc59853cfb13.png)

🔵 Once here, we must copy the following path and paste it in our regedit 

 **HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced**

🔵 Inside the path folder, we right-click and create a new **DWORD value (32-bit)**

![3Sin título](https://user-images.githubusercontent.com/115459058/223191090-d81e1f0c-1234-4379-920f-98c30070ea6a.png)

🔵 We will give it the following name: **TaskbarAcrylicOpacity** then we make sure that its value is **0**

![4Sin título](https://user-images.githubusercontent.com/115459058/223192367-210ec597-602b-4b66-9ab3-4fa809658aeb.png)

🔵 To finish, press the keys **Ctrl + Shift + Esc** and open the **task manager**, once opened, look for the **windows explorer**, right click on it and **restart** it.

![5Sin título](https://user-images.githubusercontent.com/115459058/223193143-4952683a-8bef-4854-91da-a478ff5f625c.png)

⚠ If you do not see the changes, restart your computer.

---

### What should I do if I want to get my taskbar back to normal?

🔵  Delete the WORD value (32-bit) we created earlier

![7Sin título](https://user-images.githubusercontent.com/115459058/223195127-742fc548-80d8-4fd3-9b1d-1f4c804cad90.png)


🔵 We deactivate the transparency option

![6Sin título](https://user-images.githubusercontent.com/115459058/223194669-d76dcd03-0869-4868-b039-046c861efd61.png)

⚠ To finish, press the keys **Ctrl + Shift + Esc** and open the **task manager**, once opened, look for the **windows explorer**, right click on it and **restart** it.
