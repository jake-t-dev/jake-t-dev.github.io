---
author: ["Jake Turner"]
title: "User Profile Management System"
date: "2025-02-04"
description: "A simple User Profile Management System, built using Golang and HTMX."
summary: "A simple User Profile Management System, built using Golang and HTMX."
tags: ["Go", "HTMX", "MySQL"]
---

[Github Repo](https://github.com/jake-t-dev/user-mgt-system)


# User Profile Management System

A simple User Profile Management System built to further develop my confidence in building applications using Go and HTMX.

## Project Background

I built this web application while completing the "HTMX + Go: Build Fullstack Applications with Golang and HTMX" Udemy course by [Fikayo Adepoju](https://www.linkedin.com/in/fikayoadepoju/), which i was taking to further upskill in working with HTMX and Go templating, which are technologies I have been working with during my placement year at DailyPay.

## Run Locally

Clone the project

```bash
  git clone https://github.com/jake-t-dev/user-mgt-system
```

Go to the project directory

```bash
  cd user-mgt-system
```

Ensure the MySQL image (`mysql:latest`) is running in a Docker container

``` bash
  docker ps
```

Start the server

```bash
  go run main.go
```

Navigate to [http://localhost:4000](https://localhost:4000)

