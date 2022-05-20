<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">Time tracker</h3>

  <p align="center">
    Project of time tracking app to calculate time spent on different tasks.  
    <br />
    <br />
    <a href="http://www.youtube.com/watch?feature=player_embedded&v=z3GCiZqRzxw" target="_blank">
	    <img src="http://img.youtube.com/vi/z3GCiZqRzxw/0.jpg" alt="YouTUbe video" width="240" height="180" border="0"/>
    </a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

A project meant for increasing one's productivity by tracking the time spent in front of a computer and reporting the time in a json file.

Here's why:

- Willingness to controll time spent while using pc
- Division tasks and spent time on each one
- Store all data from one work-day
- Have history of using time in json format file

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

Include all components used in the project.

- [Python 3](https://www.python.org/)
  - [Time](https://docs.python.org/3/library/time.html)
  - [Datatime](https://docs.python.org/3/library/datetime.html)
  - [Win32hui](http://timgolden.me.uk/pywin32-docs/win32gui.html)
  - [Json](https://docs.python.org/3/library/json.html)
  - [Os](https://docs.python.org/3/library/os.html)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

Instructions on setting up project locally. To get a local copy up and running follow these steps.

### Prerequisites

Things you need to use for the software and how to install them.

- cmd
  ```sh
  pip install pywin32
  ```

### Installation

_Installing and setting up app._

1. Clone the repo
   ```sh
   git clone https://github.com/filipwroblewski/TimeTracker.git
   ```
   
2. Install required modules
   ```sh
   pip install pywin32
   ```
   <p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

Run _TimeTracker.py_ and start your work.

```sh
python TimeTracker.py
```

Program automatically calculate how much time you spend on each app and display it in format h:mm:ss (h - hours, m - minutes, s - seconds). App can be run as many times in the day and data of each day are collected in the same json file.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] Collect window name
- [x] Capture when window changes
- [x] Track time spend on one window (_in seconds_)
- [x] Convert seconds to eye-friendly time format (_h:mm:ss_)
- [x] Sum all time spend using the same window name
- [x] Save all data to file
  - [x] Save to json file
  - [x] Generate json file name depending of current day
- [x] Reload data from file when in this day was created file
- [ ] Create executable (\*.exe) app
- [ ] Create app to read json file data
  - [ ] Create function to display data in eye-friendly format

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

<!-- Distributed under the ________ License. See `LICENSE.txt` for more information. -->

Distributed without any License yet.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

<a href="https://twitter.com/wrobl_ewski" ><img src="https://img.shields.io/twitter/follow/wrobl_ewski.svg?style=social"></a>

<p align="right">(<a href="#top">back to top</a>)</p>
