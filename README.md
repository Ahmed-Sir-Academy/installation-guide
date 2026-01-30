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

## Install Java (JDK)

### Step 1: Download and Install Java (JDK)
1. Open the official Java download page:
   👉 https://www.oracle.com/java/technologies/downloads/

2. Download **JDK (Java SE)** for **Windows x64**.

3. Run the downloaded installer (`.exe` file).

4. Follow the installation steps:
   - Keep default settings
   - Click **Next** → **Install**

5. After installation, note the JDK path (example):

### Step 2: Set JAVA_HOME Environment Variable

1. Press **Windows + Search** → type **Environment Variables**
2. Click **Edit the system environment variables**
3. Click **Environment Variables**
4. Under **System Variables**, click **New**

- Variable name: `JAVA_HOME`
- Variable value:
  ```
  C:\Program Files\Java\jdk-21
  ```

5. Select **Path** → Click **Edit** → **New**
6. Add:

---

