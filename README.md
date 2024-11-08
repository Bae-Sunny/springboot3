# springboot3
springboot3(JPA+OAuth2+JWT+AWS)


# 2024.11.04
## Installing Git on Mac

1. **Visit the Git website**  
   Click on the following link to access the Git homepage: [https://git-scm.com](https://git-scm.com).

2. **Click on "Download for Mac"**  
   Once on the page, follow the red arrow to click on "Download for Mac."

3. **Click on Homebrew**  
   Click on the blue text "Homebrew" to be redirected to the Homebrew installation page.

4. **Copy the installation command**  
   Follow the red arrow to click on the 📋 icon, which will copy the installation command.  
   **Installation command:**  
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
   


5. **Open the Terminal**  
   Press `Command + Space` to open Spotlight, then type "Terminal" and hit Enter.

6. **Paste the installation command**  
   In the Terminal, paste the command you copied from the Homebrew page. When prompted for a password, enter your Mac login password to start the installation.
   <img width="697" alt="스크린샷 2024-11-04 오후 9 56 50" src="https://github.com/user-attachments/assets/5cf6446d-5e82-40a6-94cb-a341de4940c2">

8. **Verify the installation**  
   After the installation is complete, you can check if Homebrew is installed correctly by running the following command in the Terminal:  
   ```bash
   brew help
   ```
   <img width="697" alt="스크린샷 2024-11-04 오후 9 57 39" src="https://github.com/user-attachments/assets/8b396a05-2ac0-4808-aea6-4ed9ef1bf54d">


## Installing Git

1. **Enter the command in the Terminal**  
   Type the following command to install Git:  
   ```bash
   brew install git
   ```
   <img width="697" alt="스크린샷 2024-11-04 오후 9 59 33" src="https://github.com/user-attachments/assets/2099654f-b978-4642-ba61-270d0eded8bc">


2. **Verify the installation**  
   To check if Git was installed correctly, enter the following command:  
   ```bash
   git --version
   ```  
   If the Git version is displayed, it confirms that the installation was successful.
   <img width="697" alt="스크린샷 2024-11-04 오후 9 56 26" src="https://github.com/user-attachments/assets/e4f4efd5-4562-4d9d-81e8-30e710b02901">



## Integrating Git with IntelliJ

1. **Open IntelliJ**  
   Launch IntelliJ IDEA. In the top menu bar, navigate to:  
   **IntelliJ IDEA > Preferences > Version Control > Git**, and then click on **Test** to verify your Git installation.
   <img width="1094" alt="스크린샷 2024-11-04 오후 10 04 04" src="https://github.com/user-attachments/assets/af4d38cf-73f8-4a86-a1d9-bf15909f36bf">

3. **Register your GitHub account**  
   - Click on **GitHub** in the Version Control settings, then select **Add Account**.  
   - Click on **Authorize in GitHub** on the JetBrains page to retrieve your GitHub login information.  
   - Once you complete the login process, your account will be automatically added to IntelliJ.

4. **Connecting a Repository in IntelliJ**
   Clone an Existing Repository
   <img width="912" alt="스크린샷 2024-11-04 오후 10 23 48" src="https://github.com/user-attachments/assets/d46f6aba-e21c-4308-9f15-a6b25ef6ed44">

   

