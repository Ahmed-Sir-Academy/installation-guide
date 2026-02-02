# installation-guide
Guide to install softwares


## Install IntelliJ IDEA

1. Open the IntelliJ IDEA download page:
   👉 [Click here to download IntelliJ IDEA for Windows](https://www.jetbrains.com/idea/download/download-thanks.html?platform=windows)
   👉 [Click here to download IntelliJ IDEA for Mac](https://www.jetbrains.com/idea/download/download-thanks.html?platform=macM1)

3. Once the download is complete, run the installer (`.exe` file).
4. When prompted for Administration access, Press Yes
5. Follow the on-screen instructions:
   - Select installation path
   - Check - **Create Desktop Shortcut**
   - Click **Next** and then **Install**

6. After installation, launch **IntelliJ IDEA** and complete the initial setup.

---

## Install Java (JDK) using IntelliJ IDEA

### Step 1: Create a New Project
1. Open **IntelliJ IDEA**
2. Click on **File → New → Project**

### Step 2: Download and Configure JDK
1. In the **JDK** section, click on **Download JDK**
2. From the dropdown, select **JDK version: 21**
3. Choose **Vendor: Eclipse Temurin**
4. Keep the **Location** as default
5. Click **OK / Next** to proceed

### Reference Screenshot
![JDK Setup in IntelliJ](https://github.com/user-attachments/assets/8eb8d13c-d1b5-4fa3-8965-bfd81cdccc7a)

### Step 3: Set JAVA_HOME Environment Variable

1. Press **Windows + Search** → type **Environment Variables**
2. Click **Edit the system environment variables**
3. Click **Environment Variables**
4. Under **System Variables**, click **New**

- Variable name: `JAVA_HOME`
- Variable value (Depends on your computer location):
  ```
  C:\Program Files\Java\jdk-21
  ```

5. Select **Path** → Click **Edit** → **New**
6. Add:

---

