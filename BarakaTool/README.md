# BARAKA TOOL V1.0

**Desktop Application ya Windows kwa usimamizi wa vifaa**

## 🚀 Features

✅ Dark Theme UI (Modern Design)  
✅ Sidebar Navigation  
✅ Support kwa: Samsung, Xiaomi, Tecno, Infinix, Oppo, Vivo  
✅ Console Output kwa logging  
✅ SQLite Database  
✅ Device Management  
✅ Backup Management  
✅ Event Logging  

## 📁 Project Structure

```
BarakaTool/
├── App.xaml
├── App.xaml.cs
├── MainWindow.xaml
├── MainWindow.xaml.cs
├── BarakaTool.csproj
├── Data/
│   └── DatabaseManager.cs
└── README.md
```

## 🛠️ Installation

1. Clone the repository
2. Open in Visual Studio 2022
3. Restore NuGet packages:
   - Material Design in XAML
   - System.Data.SQLite
   - CommunityToolkit.MVVM
4. Build and Run

## 💻 Usage

1. **Launch BARAKA TOOL**
2. **Select device brand** from sidebar (Samsung, Xiaomi, Tecno, etc.)
3. **Connect device** via USB
4. **Manage device:**
   - View device information
   - Create backups
   - Manage files
   - View logs
5. **Check console** for operation logs

## 🎨 UI Layout

- **Left Sidebar:** Navigation buttons (250px width)
- **Top Bar:** Page title and status
- **Content Area:** Dynamic content based on selection
- **Console Area:** Real-time logs (150px height)

## 🔧 Technologies

- **C#** - Programming language
- **WPF (.NET 8)** - UI Framework
- **Material Design in XAML** - Modern UI components
- **SQLite** - Database
- **MVVM Toolkit** - Application architecture

## 📊 Database Tables

### Devices
- Id, Brand, Model, SerialNumber, IMEI, AndroidVersion, Status, LastConnected

### Backups
- Id, DeviceId, BackupName, BackupSize, BackupPath, BackupDate, Status

### Logs
- Id, EventType, Message, DeviceId, Timestamp

## 👤 Author

**Baraka Tanzania**

## 📦 Version

**1.0.0**

## 📄 License

Open Source
