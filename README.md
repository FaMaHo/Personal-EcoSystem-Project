# Personal-EcoSystem-Project

## The Vision

Here will be a Planner who knows you, and a Smart Home who will adopt to your routin.

I know, it sounds scarry, who will use your data! Where is the sequrity! Yes I have the same problem with all these Smart devices. But in this project everything will be processed locally. No one has access to your data.

Okay let's stop talking and define a roadmap and start coding.

## Roadmap

### First month:

* Just a simple Flutter app with a local database (SQLite)
* We should be able to enter tasks and connect to our digital calendars (Calendar Sync).
* An ESP32 which shows the task status or priority on a LED.

> Nothing starts huge and perfect

### Second month

* Add temperature, humidity and motion sensors (PIR) - more or less, we should see
* A dashboard on the flutter app to show necessary sensor datas.
* Create notification engine 
* Including smart automations like opening curtains, circadian lighting, 
* Using Interrupts and Deep Sleep on ESP32 to wake up the system only by motion detection (PIR). (we don't want to consume all the city's electricity at the end of the project!)

### Third month

* Setting up a local model (like Llama 3 or Mistral) using Ollama as the backend.
* Upload articles and pdfs about differnt methods of planning to a local vector database to have a wise AI.
* Analyze open applications on the laptop and compare it to the active task in Planner. (You can't cheet! Your planner knows what you are doing!)
* Create a system that if ActivityWatch detects that you're scrolling through YouTube, Planner will issue a message and change the desk light to "alert" mode.

Take care of optimizing the response speed of the AI ​​model on local hardware.

### Fourth month

* Flutter UI that changes based on the previous week's focus score or different planning patterns based on psychology articles and AI suggestions.
* Using ESP32-Cam and implementing a lightweight model for Human Pose Estimation (only skeletal body points for privacy)
* Detects slouching at the desk and small vibrations on the chair or table as an alert.
* If the gaze is directed towards the phone for a long time, the system detects distraction.

---

> Let's see how much I can avoid using AI!