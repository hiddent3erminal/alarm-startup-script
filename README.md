# 🚗 Old Car Startup Sound Effect Script

This `bash` script uses the `beep` command to simulate the distinct sounds of an old car struggling to start, eventually roaring to life, and then settling into a smooth purr. It's a fun way to add some auditory flair to your terminal!

## 🎥 Demo

(Consider adding a GIF or a short video demonstrating the script in action here once you have it running!)

## ✨ Features

* **Realistic Sound Progression**: Mimics the full startup sequence, from initial cranks and sputtering to a final smooth engine purr.
* **`beep` Command Utilization**: Leverages the `beep` utility for precise frequency and duration control, creating varied sound effects.
* **Customizable**: Easily modify frequencies, durations, and delays to fine-tune the sound effects.

## ⚙️ Prerequisites

To run this script, you need to have the `beep` utility installed on your system.

### Installation on Debian/Ubuntu

```bash
sudo apt-get install beep
Installation on Fedora
Bash

sudo dnf install beep
Installation on Arch Linux
Bash

sudo pacman -S beep
Note: You might need to give your user appropriate permissions to access the PC speaker. This often involves adding your user to the input group or configuring modprobe.

🚀 How to Use
Save the script: Save the provided content as alarm.sh (or any other desired filename).
Make it executable:
Bash

chmod +x alarm.sh
Run the script:
Bash

./alarm.sh
📜 Script Breakdown
The script uses a series of beep commands with different frequencies (-f) and durations (-l) to create the various sound effects:

Starter cranking... struggling: A series of decreasing frequencies with short durations, mimicking the struggle of the starter motor.
Failed ignition attempt: Lower frequencies and shorter durations for a quick, unsuccessful attempt.
Second attempt, still cranky: Repetitive, slightly higher frequency beeps.
Sputtering... trying again...: A mix of lower frequencies and short beeps, representing the engine trying to catch.
Engine finally catches!: A loop that progressively increases the frequency, simulating the engine revving up.
Purrs smoothly: Consistent mid-range frequency beeps for a steady engine idle sound.
Final confirmation horn beep: A quick, high-frequency beep to signify a successful start.
🤝 Contributing
Feel free to fork this repository, suggest improvements, or submit pull requests. If you have ideas for other sound effects or refinements, I'd love to hear them!

📄 License
This project is open-source and available under the MIT License.