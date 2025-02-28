# 💰 Finance Tracker

A simple and intuitive finance tracker application built with C++ and Qt to help you manage your expenses and savings.

## 📋 Features
- Track income and expenses
- View spending summaries with interactive charts
- User-friendly interface built with Qt

## Prerequisites  
- **Qt 6.x** – Download from [Qt Official Site](https://www.qt.io/download)  
- **CMake 3.16 or higher** – [Download CMake](https://cmake.org/download/)

## Installation and Setup  
1. **Clone the repository:**  
    ```bash
    git clone https://github.com/Keano20/Finance-Tracker.git
    cd Finance-Tracker
    ```

2. **Configure CMake:**  
    In CLion, go to **File > Settings > Build, Execution, Deployment > CMake** and add:  
    ```plaintext
    -DCMAKE_PREFIX_PATH="path/to/Qt/6.x.x/gcc_64"
    
    ```
    Replace path/to/Qt/6.x.x/gcc_64 with the actual path where Qt is installed. For example:
   
	•	On Windows: C:/Qt/6.x.x/mingw_64

	•	On Mac: /Users/username/Qt/6.x.x/clang_64

	•	On Linux: /home/username/Qt/6.x.x/gcc_64


4. **Build and Run:**  
    - Open the project in **CLion**.  
    - Click **Build > Build Project**.  
    - Click **Run** to launch the application.  


---

Happy tracking! 💸
