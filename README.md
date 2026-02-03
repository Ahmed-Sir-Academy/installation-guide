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

## Download / Create a Maven Project using IntelliJ IDEA

### Step 1: Create New Project
1. Open **IntelliJ IDEA**
2. Click on **File → New → Project**

### Step 2: Select Maven
1. From the left panel, select **Maven**
2. Select **Project SDK** (JDK 17 or JDK 21)
3. Check **Create from Archetype** (optional for beginners)
4. Click **Next**

### Step 3: Project Details
1. Enter **GroupId**  
   Example: `com.ahmedsiracademy`
2. Enter **ArtifactId**  
   Example: `maven-demo`
3. Version will auto-generate (keep default)
4. Click **Next**

### Step 4: Maven Settings
1. **Maven Home Path**: Select **Bundled (Maven 3.x)**  
   _(Recommended – no manual download needed)_
2. **User Settings File**: Leave default
3. **Local Repository**: Leave default
4. Click **Finish**

### Step 5: Maven Dependencies Download
- IntelliJ will automatically download:
  - Maven
  - Required plugins
  - Dependencies
- Wait until indexing completes


---

# Install PostgreSQL on Windows

## Step 1: Download PostgreSQL

1. Open the official PostgreSQL website:
   👉 [Click here to install PostgreSQL](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)

2. Click **Download the installer**.

3. You will be redirected to **EDB (EnterpriseDB)** website.
   - Download the latest **Windows x64** installer.

## Step 2: Run the Installer

1. Double-click the downloaded `.exe` file.
2. Click **Next** on the setup wizard.

## Step 3: Choose Installation Directory

1. Keep the default path (recommended):

## Step 4: Enter password as `admin123` for user name `postgres`

## Step 5: Leave the default port `5432`


