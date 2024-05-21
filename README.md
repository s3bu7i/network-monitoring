<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/6295/6295417.png" width="100" />
</p>
<p align="center">
    <h1 align="center">NETWORK-MONITORING</h1>
</p>

<p align="center">
	<img src="https://img.shields.io/github/license/s3bu7i/network-monitoring.git?style=flat&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/s3bu7i/network-monitoring.git?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/s3bu7i/network-monitoring.git?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/s3bu7i/network-monitoring.git?style=flat&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/GNU%20Bash-4EAA25.svg?style=flat&logo=GNU-Bash&logoColor=white" alt="GNU%20Bash">
	<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=flat&logo=HTML5&logoColor=white" alt="HTML5">
	<img src="https://img.shields.io/badge/Redis-DC382D.svg?style=flat&logo=Redis&logoColor=white" alt="Redis">
	<img src="https://img.shields.io/badge/YAML-CB171E.svg?style=flat&logo=YAML&logoColor=white" alt="YAML">
	<img src="https://img.shields.io/badge/Poetry-60A5FA.svg?style=flat&logo=Poetry&logoColor=white" alt="Poetry">
	<img src="https://img.shields.io/badge/Celery-37814A.svg?style=flat&logo=Celery&logoColor=white" alt="Celery">
	<br>
	<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
	<img src="https://img.shields.io/badge/Docker-2496ED.svg?style=flat&logo=Docker&logoColor=white" alt="Docker">
	<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF.svg?style=flat&logo=GitHub-Actions&logoColor=white" alt="GitHub%20Actions">
	<img src="https://img.shields.io/badge/pandas-150458.svg?style=flat&logo=pandas&logoColor=white" alt="pandas">
	<img src="https://img.shields.io/badge/Django-092E20.svg?style=flat&logo=Django&logoColor=white" alt="Django">
	<img src="https://img.shields.io/badge/NumPy-013243.svg?style=flat&logo=NumPy&logoColor=white" alt="NumPy">
</p>
<hr>

## 🔗 Quick Links

> - [📍 Overview](#-overview)
> - [📦 Features](#-features)
> - [📂 Repository Structure](#-repository-structure)
> - [🧩 Modules](#-modules)
> - [🚀 Getting Started](#-getting-started)
>   - [⚙️ Installation](#️-installation)
>   - [🤖 Running network-monitoring](#-running-network-monitoring)
>   - [🧪 Tests](#-tests)
> - [🛠 Project Roadmap](#-project-roadmap)
> - [🤝 Contributing](#-contributing)
> - [📄 License](#-license)
> - [👏 Acknowledgments](#-acknowledgments)

---

## 📍 Overview

<code>► NetworkMonitor is a powerful tool designed to monitor network performance, detect outages, and provide detailed analytics. It is containerized using Docker for easy deployment and scalability.</code>

---

## 📦 Features

<code>
Real-time network monitoring
Alerts for network issues
Detailed analytics and reporting
Easy deployment with Docker</code>

---

## 📂 Repository Structure

```sh
└── network-monitoring/
    ├── .github
    │   └── workflows
    │       ├── docker-image.yml
    │       ├── jekyll-gh-pages.yml
    │       └── static.yml
    ├── README.md
    ├── docker-compose.yml
    ├── network
    │   ├── .dockerignore
    │   ├── Dockerfile
    │   ├── main
    │   │   ├── __init__.py
    │   │   ├── __pycache__
    │   │   │   └── __init__.cpython-312.pyc
    │   │   ├── admin.py
    │   │   ├── apps.py
    │   │   ├── consumers.py
    │   │   ├── forms.py
    │   │   ├── models.py
    │   │   ├── net_services
    │   │   │   ├── netmiko_queries.py
    │   │   │   └── restconf_queries.py
    │   │   ├── routing.py
    │   │   ├── static
    │   │   │   └── main
    │   │   │       ├── css
    │   │   │       ├── download
    │   │   │       ├── fonts
    │   │   │       ├── img
    │   │   │       └── js
    │   │   ├── tasks.py
    │   │   ├── templates
    │   │   │   └── main
    │   │   │       ├── _base.html
    │   │   │       ├── add_devices_multiple.html
    │   │   │       ├── add_devices_single.html
    │   │   │       ├── all_devices.html
    │   │   │       ├── device_detail.html
    │   │   │       ├── index.html
    │   │   │       ├── refresh_all.html
    │   │   │       ├── reports_device_stats.html
    │   │   │       ├── reports_licensing.html
    │   │   │       ├── reports_oneview.html
    │   │   │       ├── tools_enable_restconf.html
    │   │   │       ├── tools_logs.html
    │   │   │       └── tools_raw_json.html
    │   │   ├── tests.py
    │   │   ├── urls.py
    │   │   └── views.py
    │   ├── manage.py
    │   ├── network
    │   │   ├── __init__.py
    │   │   ├── __pycache__
    │   │   │   ├── __init__.cpython-311.pyc
    │   │   │   ├── __init__.cpython-312.pyc
    │   │   │   ├── asgi.cpython-311.pyc
    │   │   │   ├── celery.cpython-311.pyc
    │   │   │   └── celery.cpython-312.pyc
    │   │   ├── asgi.py
    │   │   ├── celery.py
    │   │   ├── settings_production.py
    │   │   └── urls.py
    │   ├── poetry.lock
    │   ├── requirements.txt
    │   ├── start_johann.sh
    │   └── stickydata
    │       ├── db.sqlite3
    │       └── debug.log
    └── nginx
        ├── .dockerignore
        ├── Dockerfile
        └── nginx.conf
```

---

## 🧩 Modules

<details closed><summary>.</summary>

| File                                                                                                  | Summary                         |
| ---                                                                                                   | ---                             |
| [docker-compose.yml](https://github.com/s3bu7i/network-monitoring.git/blob/master/docker-compose.yml) | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>nginx</summary>

| File                                                                                        | Summary                         |
| ---                                                                                         | ---                             |
| [nginx.conf](https://github.com/s3bu7i/network-monitoring.git/blob/master/nginx/nginx.conf) | <code>► INSERT-TEXT-HERE</code> |
| [Dockerfile](https://github.com/s3bu7i/network-monitoring.git/blob/master/nginx/Dockerfile) | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>network</summary>

| File                                                                                                      | Summary                         |
| ---                                                                                                       | ---                             |
| [start_johann.sh](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/start_johann.sh)   | <code>► INSERT-TEXT-HERE</code> |
| [Dockerfile](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/Dockerfile)             | <code>► INSERT-TEXT-HERE</code> |
| [poetry.lock](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/poetry.lock)           | <code>► INSERT-TEXT-HERE</code> |
| [manage.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/manage.py)               | <code>► INSERT-TEXT-HERE</code> |
| [requirements.txt](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/requirements.txt) | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>network.main</summary>

| File                                                                                                   | Summary                         |
| ---                                                                                                    | ---                             |
| [admin.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/admin.py)         | <code>► INSERT-TEXT-HERE</code> |
| [apps.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/apps.py)           | <code>► INSERT-TEXT-HERE</code> |
| [tasks.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/tasks.py)         | <code>► INSERT-TEXT-HERE</code> |
| [tests.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/tests.py)         | <code>► INSERT-TEXT-HERE</code> |
| [views.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/views.py)         | <code>► INSERT-TEXT-HERE</code> |
| [consumers.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/consumers.py) | <code>► INSERT-TEXT-HERE</code> |
| [routing.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/routing.py)     | <code>► INSERT-TEXT-HERE</code> |
| [urls.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/urls.py)           | <code>► INSERT-TEXT-HERE</code> |
| [forms.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/forms.py)         | <code>► INSERT-TEXT-HERE</code> |
| [models.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/models.py)       | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>network.main.net_services</summary>

| File                                                                                                                              | Summary                         |
| ---                                                                                                                               | ---                             |
| [restconf_queries.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/net_services/restconf_queries.py) | <code>► INSERT-TEXT-HERE</code> |
| [netmiko_queries.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/net_services/netmiko_queries.py)   | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>network.main.templates.main</summary>

| File                                                                                                                                              | Summary                         |
| ---                                                                                                                                               | ---                             |
| [tools_raw_json.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/tools_raw_json.html)               | <code>► INSERT-TEXT-HERE</code> |
| [tools_logs.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/tools_logs.html)                       | <code>► INSERT-TEXT-HERE</code> |
| [device_detail.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/device_detail.html)                 | <code>► INSERT-TEXT-HERE</code> |
| [reports_oneview.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/reports_oneview.html)             | <code>► INSERT-TEXT-HERE</code> |
| [index.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/index.html)                                 | <code>► INSERT-TEXT-HERE</code> |
| [add_devices_multiple.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/add_devices_multiple.html)   | <code>► INSERT-TEXT-HERE</code> |
| [all_devices.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/all_devices.html)                     | <code>► INSERT-TEXT-HERE</code> |
| [reports_licensing.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/reports_licensing.html)         | <code>► INSERT-TEXT-HERE</code> |
| [refresh_all.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/refresh_all.html)                     | <code>► INSERT-TEXT-HERE</code> |
| [_base.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/_base.html)                                 | <code>► INSERT-TEXT-HERE</code> |
| [reports_device_stats.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/reports_device_stats.html)   | <code>► INSERT-TEXT-HERE</code> |
| [add_devices_single.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/add_devices_single.html)       | <code>► INSERT-TEXT-HERE</code> |
| [tools_enable_restconf.html](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/main/templates/main/tools_enable_restconf.html) | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>network.network</summary>

| File                                                                                                                          | Summary                         |
| ---                                                                                                                           | ---                             |
| [asgi.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/network/asgi.py)                               | <code>► INSERT-TEXT-HERE</code> |
| [celery.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/network/celery.py)                           | <code>► INSERT-TEXT-HERE</code> |
| [urls.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/network/urls.py)                               | <code>► INSERT-TEXT-HERE</code> |
| [settings_production.py](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/network/settings_production.py) | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>network.stickydata</summary>

| File                                                                                                     | Summary                         |
| ---                                                                                                      | ---                             |
| [db.sqlite3](https://github.com/s3bu7i/network-monitoring.git/blob/master/network/stickydata/db.sqlite3) | <code>► INSERT-TEXT-HERE</code> |

</details>

<details closed><summary>.github.workflows</summary>

| File                                                                                                                      | Summary                         |
| ---                                                                                                                       | ---                             |
| [jekyll-gh-pages.yml](https://github.com/s3bu7i/network-monitoring.git/blob/master/.github/workflows/jekyll-gh-pages.yml) | <code>► INSERT-TEXT-HERE</code> |
| [static.yml](https://github.com/s3bu7i/network-monitoring.git/blob/master/.github/workflows/static.yml)                   | <code>► INSERT-TEXT-HERE</code> |
| [docker-image.yml](https://github.com/s3bu7i/network-monitoring.git/blob/master/.github/workflows/docker-image.yml)       | <code>► INSERT-TEXT-HERE</code> |

</details>

---

## 🚀 Getting Started

***Requirements***

Ensure you have the following dependencies installed on your system:

* **Python**: `version x.y.z`

### ⚙️ Installation

1. Clone the network-monitoring repository:

```sh
git clone https://github.com/s3bu7i/network-monitoring.git
```

2. Change to the project directory:

```sh
cd network-monitoring
```

3. Install the dependencies:

```sh
pip install -r requirements.txt
```

### 🤖 Running network-monitoring

Use the following command to run network-monitoring:

```sh
python main.py
```

### 🧪 Tests

To execute tests, run:

```sh
pytest
```


## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/s3bu7i/network-monitoring.git/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/s3bu7i/network-monitoring.git/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/s3bu7i/network-monitoring.git/issues)**: Submit bugs found or log feature requests for Network-monitoring.

<details closed>
    <summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone https://github.com/s3bu7i/network-monitoring.git
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

## 📄 License

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

## 👏 Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#-quick-links)

---
