
<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>
matrix-dashboard
</h1>
<h3 align="center">📍 Make Your Life Easier with Matrix-Dashboard</h3>
<h3 align="center">🚀 Developed with the software and tools below.</h3>
<p align="center">

<img src="https://img.shields.io/badge/Markdown-000000.svg?style=for-the-badge&logo=Markdown&logoColor=white" alt="" />
<img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white" alt="png" />
</p>

</div>

---
## 📚 Table of Contents
- [📚 Table of Contents](#-table-of-contents)
- [📍Overview](#-introdcution)
- [🔮 Features](#-features)
- [⚙️ Project Structure](#project-structure)
- [🧩 Modules](#modules)
- [🏎💨 Getting Started](#-getting-started)
- [🗺 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [🪪 License](#-license)
- [📫 Contact](#-contact)
- [🙏 Acknowledgments](#-acknowledgments)

---

## 📍Overview

Matrix-Dashboard is a powerful open-source project dashboard for managing virtual environments within a GitHub repository. It allows users to view key information about their project including current tasks and progress, test

## 🔮 Feautres

> `[📌  INSERT-PROJECT-FEATURES]`

---

<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-github-open.svg" width="80" />

## ⚙️ Project Structure


---

<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-src-open.svg" width="80" />

## 💻 Modules
<details closed><summary>Apps_v2</summary>

| File              | Summary                                                                                                                                                                                                                                                | Module                         |
|:------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------|
| gif_viewer.py     | This code is for a GifScreen class which is used to display gifs on a canvas . It has methods to switch between gifs , toggle display , and switch between apps . It also has a select mode which allows the user to select                            | impl/apps_v2/gif_viewer.py     |
| stocks.py         | This code creates a StocksVerticalScreen class that displays stock prices and symbols from the ticker_symbols list . It uses the yfinance library to get the stock prices and the PIL library to draw the symbols and                                  | impl/apps_v2/stocks.py         |
| notion_v2.py      | This code is for a NotionScreen class that is used to display tasks from a Notion database . It uses the PIL library to draw the tasks onto a canvas , and the requests library to fetch the tasks from the Notion database .                          | impl/apps_v2/notion_v2.py      |
| main_screen.py    | This code is for the MainScreen class in the apps_v2 package . It is used to generate a frame for the display of a device . It has three themes : sakura , cloud , and forest . It displays the time ,                                                 | impl/apps_v2/main_screen.py    |
| spotify_player.py | This code is for the SpotifyScreen class , which is used to generate a display for a Spotify player . It takes in a configuration , modules , and default actions as parameters , and uses them to generate a display with the current song 's title , | impl/apps_v2/spotify_player.py |
| weather.py        | This code is part of a class that generates a weather screen for a display . It imports necessary libraries , sets up the font , color , and icon variables , and then generates the weather screen based on the input status . It also includes a     | impl/apps_v2/weather.py        |
| subcount.py       | This code is for a SubcountScreen class that displays the number of subscribers of a YouTube channel . It uses the PIL library to draw the text onto an image , and the urllib library to fetch the number of subscribers from the YouTube             | impl/apps_v2/subcount.py       |
| life.py           | This code is for a Game of Life Screen class that is used to generate a Conway 's Game of Life animation . It includes functions to generate a random state , fetch patterns , generate a new color , and calculate the number of neighbors for a      | impl/apps_v2/life.py           |
| pomodoro.py       | This code is for a Pomodoro Screen class which is used to generate a timer screen for the Pomodoro Technique . It has methods to initialize the class , generate the screen , and handle input status . It also has variables to store the work        | impl/apps_v2/pomodoro.py       |

</details>

<details closed><summary>Cad</summary>

| File                            | Summary                              | Module                              |
|:--------------------------------|:-------------------------------------|:------------------------------------|
| matrix back swivel V2.STEP      | Prompt too long to generate summary. | cad/matrix back swivel V2.STEP      |
| matrix front v3.STEP            | Prompt too long to generate summary. | cad/matrix front v3.STEP            |
| matrix back swivel back V2.STEP | Prompt too long to generate summary. | cad/matrix back swivel back V2.STEP |
| base swivel V2.STEP             | Prompt too long to generate summary. | cad/base swivel V2.STEP             |
| base swivel cap V2.STEP         | Prompt too long to generate summary. | cad/base swivel cap V2.STEP         |
| matrix midplate v3.STEP         | Prompt too long to generate summary. | cad/matrix midplate v3.STEP         |
| knob.STEP                       | Prompt too long to generate summary. | cad/knob.STEP                       |
| matrix base v3.STEP             | Prompt too long to generate summary. | cad/matrix base v3.STEP             |
| swivel retainer full cover.STEP | Prompt too long to generate summary. | cad/swivel retainer full cover.STEP |
| matrix back v3.STEP             | Prompt too long to generate summary. | cad/matrix back v3.STEP             |
| matrix base bot panel.STEP      | Prompt too long to generate summary. | cad/matrix base bot panel.STEP      |

</details>

<details closed><summary>Fonts</summary>

| File     | Summary                                                                                                            | Module              |
|:---------|:-------------------------------------------------------------------------------------------------------------------|:--------------------|
| tiny.otf | This code is an error message indicating that a file could not be decoded because it is not a text or UTF-8 file . | impl/fonts/tiny.otf |

</details>

<details closed><summary>Impl</summary>

| File             | Summary                                                                                                                                                                                                                          | Module                |
|:-----------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------|
| controller_v3.py | This code is a Python script that sets up a Raspberry Pi with an LED matrix display . It configures the display , sets up input devices such as a rotary encoder and tilt switch , and creates a list of apps to be displayed on | impl/controller_v3.py |
| InputStatus.py   | This code creates an Enum class called InputStatusEnum , which contains seven different values that represent different types of user input .                                                                                    | impl/InputStatus.py   |

</details>

<details closed><summary>Life_patterns</summary>

| File           | Summary                                                                                                            | Module                                        |
|:---------------|:-------------------------------------------------------------------------------------------------------------------|:----------------------------------------------|
| centinal.npy   | This code is an error message indicating that a file could not be decoded because it is not a text or UTF-8 file . | impl/apps_v2/res/life_patterns/centinal.npy   |
| pboj_p22.npy   | This code is an error message indicating that a file could not be decoded because it is not a text or UTF-8 file . | impl/apps_v2/res/life_patterns/pboj_p22.npy   |
| achim_p144.npy | This code is an error message indicating that a file could not be decoded because it is not a text or UTF-8 file . | impl/apps_v2/res/life_patterns/achim_p144.npy |

</details>

<details closed><summary>Modules</summary>

| File                   | Summary                                                                                                                                                                                                                                                        | Module                              |
|:-----------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------|
| weather_module.py      | time.sleep(10 )                                                                                                                                                                                                                                                | impl/modules/weather_module.py      |
|                        |                                                                                                                                                                                                                                                                |                                     |
|                        |  This code creates a WeatherModule class that uses the PyOWM library to get weather data from the OpenWeatherMap API . It uses a thread to update the weather data every 10 seconds and stores the                                                             |                                     |
| spotify_module.py      | This code creates a SpotifyModule class that uses the Spotipy library to interact with the Spotify API . It requires a config file with the client_id , client_secret , and redirect_uri to authenticate the user . The class                                  | impl/modules/spotify_module.py      |
| notification_module.py | This code creates a NotificationModule class that uses a websocket to receive notifications from a Pushbullet service . It parses a white list of applications and stores notifications in a queue . It also provides a getNotificationList ( ) method to sort | impl/modules/notification_module.py |

</details>

<details closed><summary>Root</summary>

| File                | Summary                                                                                                                                                                                                                | Module              |
|:--------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------|
| config template.txt | This code provides configuration settings for various services , including Pushbullet , OpenWeatherMap , Spotify , Notion , Notion_V2 , and Youtube . It includes credentials such as tokens , client IDs , and keys . | config template.txt |

</details>
<hr />

## 🚀 Getting Started

### ✅ Prerequisites

Before you begin, ensure that you have the following prerequisites installed:
> `[📌  INSERT-PROJECT-PREREQUISITES]`

### 💻 Installation

1. Clone the matrix-dashboard repository:
```sh
git clone https://github.com/allenslab/matrix-dashboard
```

2. Change to the project directory:
```sh
cd matrix-dashboard
```

3. Install the dependencies:
```sh
pip install -r requirements.txt
```

### 🤖 Using matrix-dashboard

```sh
python main.py
```

### 🧪 Running Tests
```sh
#run tests
```

<hr />

## 🛠 Future Development
- [X] [📌  COMPLETED-TASK]
- [ ] [📌  INSERT-TASK]
- [ ] [📌  INSERT-TASK]


---

## 🤝 Contributing
Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a pull request to the original repository.
Open a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 🪪 License

This project is licensed under the `[📌  INSERT-LICENSE-TYPE]` License. See the [LICENSE](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository) file for additional info.

---

## 🙏 Acknowledgments

[📌  INSERT-DESCRIPTION]


---

