# ⏰ Python Tkinter Alarm Clock

A simple Alarm Clock application built using Python's Tkinter GUI library. Users can set an alarm time in 24-hour format, and the application will play a sound when the specified time is reached.

## 🚀 Features

* Simple and user-friendly GUI
* Set alarm using Hours, Minutes, and Seconds
* Supports 24-hour time format
* Plays an alarm sound when the set time is reached
* Built with Python and Tkinter


> Add a screenshot of your application and save it as `screenshot.png` in the repository.

## 🛠️ Technologies Used

* Python 3
* Tkinter (GUI)
* Datetime Module
* Time Module
* Winsound Module (Windows)

## 📂 Project Structure

```
Alarm-Clock/
│
├── alarm_clock.py
├── Music.wav
├── screenshot.png
└── README.md
```

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/alarm-clock.git
```

2. Navigate to the project folder:

```bash
cd alarm-clock
```

3. Run the Python file:

```bash
python alarm_clock.py
```

## 🔧 Requirements

* Python 3.x
* Windows OS (because `winsound` is used)

No additional libraries need to be installed.

## 📖 Usage

1. Launch the application.
2. Enter the alarm time in **24-hour format**.
3. Click **"Set Your Alarm"**.
4. When the current time matches the alarm time, the alarm sound will play.

### Example

```
Hour: 14
Min : 30
Sec : 00
```

Alarm will ring at **2:30:00 PM**.

## ⚠️ Note

* Make sure `Music.wav` is present in the same directory as the Python file.
* The application currently works only on Windows due to the use of the `winsound` module.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

## 📄 License

This project is open-source and available under the MIT License.

---

Made with ❤️ using Python and Tkinter.
