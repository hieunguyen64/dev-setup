# Setup React Native for Windows

# Setup for Android Studio

- Nhấn vào “More Actions” sau đó chọn SDK Manager
- Ở Tab “SDK Platforms” tích vào mục Show Package Details
- Sau đó ở dropdown Android 12.0 (S) tích vào các mục :
    - `Android SDK Platform 3`
    - **`Intel x86 Atom_64 System Image`**
    - `Google APIs Intel x86 Atom System Image`
    

# Setup for NodeJS

[Node v16.16.0 (LTS) | Node.js (nodejs.org)](https://nodejs.org/en/blog/release/v16.16.0/)

Tick vào mục bên dưới khi cài đặt để cài thư viện Chocolatey

![image](https://user-images.githubusercontent.com/58379892/220813691-a06908ae-a2ec-49ec-95ea-0366bdac5a14.png)

npm i yarn -g 

# Setup for Java

- [Java Archive Downloads - Java SE 11 | Oracle Vietnam](https://www.oracle.com/vn/java/technologies/javase/jdk11-archive-downloads.html)
- Vào đường link phía trên và tải ****Java SE Development Kit 11.0.17****

# Setup Environment

- Tạo biến JAVA_HOME
    1. Tìm kiếm Edit the system Environment variables
    2. Ở Tab Advance chọn `Environment Variables`
    3. Ở mục System variables ấn vào nút `New`
    
    ![image](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/aad6dc9f-34b3-44b3-9477-f1cce30b5ed8/Untitled.png)
    
- Tạo biến ANDROID_HOME
    1. Tìm kiếm Edit the system Environment variables
    2. Ở Tab Advance chọn `Environment Variables`
    3. Ở mục System variables ấn vào nút `New`
    
    ![image](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3891c958-bd29-4754-bbc3-ca19163dbf5a/Untitled.png)
    
- Thêm **`platform-tools`** vào Path
    1. Tìm kiếm Edit the system Environment variables
    2. Ở Tab Advance chọn `Environment Variables`
    3. Chọn mục Path
    4. Ấn vào nút Edit
    5. Ấn vào nút New và paste `%LOCALAPPDATA%\Android\Sdk\platform-tools`
- Thêm JAVA ****vào Path
