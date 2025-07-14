# barabylka-injector
Самописный Injector на языке python. Инжект происходит в режиме Stealth-Inject.

# **BARABYLKA SAMOPIS - STEALTH INJECTOR**  

**Advanced stealth DLL injector with process selection and visual feedback**  

## 🔥 **Features**  
✔ **Stealth Injection** - Hidden console window and minimal system interaction  
✔ **Process Selection** - Dynamic list of running processes with refresh option  
✔ **DLL Browser** - Easy file selection with path validation  
✔ **Visual Feedback** - Progress bar and status notifications  
✔ **Modern UI** - Sleek dark theme with smooth animations  
✔ **Error Handling** - Comprehensive error detection and reporting  

## 🛠 **Technical Details**  
- **Injection Method**: `CreateRemoteThread` + `LoadLibraryA`  
- **Process Access**: Full privileges with proper handle cleanup  
- **Memory Management**: Safe allocation/deallocation of remote memory  
- **UI Framework**: PyQt5 with custom styling  
- **Compatibility**: Windows 10/11 (x86/x64)  

## 📦 **Installation**  
1. Install Python 3.10+  
2. Install dependencies:  
   ```bash
   pip install PyQt5
   ```
3. Place your DLL files in the same directory  

## 🚀 **Usage**  
1. Select target process from dropdown  
2. Browse and select your DLL file  
3. Click "STEALTH INJECT"  
4. Monitor progress bar and status updates  

## 📜 **Code Structure**  
```
vexis_injector.py  
│  
├── UI Components  
│   ├── Process selector with auto-refresh  
│   ├── DLL file browser  
│   └── Animated injection button  
│  
├── Injection Core  
│   ├── Process memory operations  
│   ├── Remote thread creation  
│   └── Error handling  
│  
└── Visual Feedback  
    ├── Progress bar  
    ├── Status notifications  
    └── Color-coded alerts  
```

## ⚠ **Disclaimer**  
For educational purposes only. Use responsibly and only on systems you own.  

---

 

**License:** MIT  
**Author:** vityanvsk

🔗 *Clone and star the repo to support development!*  

---

### 📝 **Recommended GitHub Additions**  
1. Add actual screenshot to `/images` folder  
2. Include sample DLL for testing  
3. Add requirements.txt for dependencies  
4. Create release builds with PyInstaller  

Would you like me to generate any additional files (README.md, requirements.txt, etc.) for your GitHub repository?
