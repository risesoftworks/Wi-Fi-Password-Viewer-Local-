# Wi-Fi Password Viewer (Local)

Simple Windows console app to view the password of a saved Wi-Fi network.

---

## Features

- Enter any saved Wi-Fi SSID
- Shows password if accessible
- Works on Windows, no compiler needed

---

## How to Use

1. Download and run `wifi_viewer.exe`.
2. Find your SSID:
   - Open Command Prompt (`Win + R` → `cmd`) or (Win  → cmd) 
   - Run:  
     ```
     netsh wlan show interfaces
     ```
   - Look for the line `SSID : YourNetworkName`
3. Enter the SSID in the program.
4. View the password.
5. Press any key to exit.

---

## Notes

- Only works for saved Wi-Fi networks
- Does **not** work for Ethernet
- Use on networks you own or have permission for

---

## License

MIT License