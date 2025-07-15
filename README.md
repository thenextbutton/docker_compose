# 🐳 Docker Compose Stacks

This repository contains various Docker Compose configurations for self-hosted applications and services. Each subdirectory represents a distinct Docker Compose stack, allowing for easy deployment and management of individual services.

---

## 📋 Table of Contents

* [🏠 AdGuard Home Sync](#-adguard-home-sync)
* [📚 Audiobookshelf](#-audiobookshelf)
* [🌐 DDNS Updater](#-ddns-updater)
* [📹 Frigate](#-frigate)
* [💚 Gatus](#-gatus)
* [📊 Glances](#-glances)
* [🚀 Homepage](#-homepage)
* [🖼 Koillection](#️-koillection)
* [▶ MeTube](#️-metube)
* [🚨 NetAlertX](#-netalertx)
* [⚙️ Nginx Proxy Manager](#️-nginx-proxy-manager)
* [🔔 Ntfy](#-ntfy)
* [⏰ NTP](#-ntp)
* [⚡ Speedtest Tracker](#-speedtest-tracker)
* [📄 Static Web Server](#-static-web-server)
* [🍿 Tautulli](#-tautulli)
* [🗄️ Tiny Media Manager](#️-tiny-media-manager)
* [✅ Uptime Kuma](#-uptime-kuma)
* [🔐 Vaultwarden](#-vaultwarden)
* [💰 Wallos](#-wallos)
* [🔄 Watchtower](#-watchtower)

---

## 🏠 AdGuard Home Sync

The stack provides the necessary components to synchronize configurations between multiple **AdGuard Home** instances. It's ideal for maintaining consistent ad-blocking rules and settings across different devices or locations.

---

## 📚 Audiobookshelf


Directory contains the Docker Compose setup for **Audiobookshelf**, a self-hosted audiobook and podcast server. It allows you to organize, stream, and listen to your audio content from anywhere.

---

## 🌐 DDNS Updater

Configuration deploys a **Dynamic DNS (DDNS) updater** service. It's used to automatically update your domain's A/AAAA records with your current public IP address, ensuring your services remain accessible even if your IP changes.

---

## 📹 Frigate


Stack is for **Frigate**, an open-source NVR (Network Video Recorder) with AI object detection. It utilizes a Google Coral TPU (or CPU) to process video streams from IP cameras and detect objects like people, cars, and animals, triggering recordings and notifications.

---

## 💚 Gatus

Directory contains the Docker Compose setup for **Gatus**, a health dashboard. It allows you to monitor the status and uptime of your services and websites, providing alerts and visual feedback on their availability.

---

## 📊 Glances


Configuration runs **Glances**, a cross-platform system monitoring tool. It provides a comprehensive overview of your server's resources, including CPU, memory, disk I/O, network usage, and running processes.

---

## 🚀 Homepage

Stack sets up a customizable **homepage** for your self-hosted services. It acts as a central dashboard, providing quick access to all your applications and displaying relevant information at a glance.

---

## 🖼 Koillection

Directory contains the Docker Compose setup for **Koillection**, a self-hosted collection management tool. It helps you organize and catalog your physical and digital collections, such as movies, books, games, or anything else you collect.

---

## ▶ MeTube


Configuration deploys **MeTube**, a web GUI for `yt-dlp`. It allows you to easily download videos and audio from various online platforms through a user-friendly interface.

---

## 🚨 NetAlertX

Stack is for **NetAlertX**, a network monitoring and alerting tool. It helps you keep track of devices on your network, detect new devices, and receive alerts for changes or intrusions.

---

## ⚙ Nginx Proxy Manager


Directory contains the Docker Compose setup for **Nginx Proxy Manager**. This tool provides a simple web interface to manage Nginx proxy hosts with free SSL certificates from Let's Encrypt, making it easy to expose your self-hosted services securely.

---

## 🔔 Ntfy

Configuration deploys **Ntfy**, a simple HTTP-based push notification service. It allows you to send push notifications to your phone or desktop from scripts or applications.

---

## ⏰ NTP

Stack sets up a local **NTP (Network Time Protocol) server**. This can be useful for ensuring accurate time synchronization across all devices on your local network, especially in environments where internet access is limited or precise timekeeping is critical.

---

## ⚡ Speedtest Tracker

Directory contains the Docker Compose setup for **Speedtest Tracker**. It periodically runs speed tests and logs the results, allowing you to monitor your internet connection's performance over time.

---

## 📄 Static Web Server

Configuration provides a simple **static web server**. It's ideal for hosting static HTML, CSS, and JavaScript files, or serving as a lightweight web server for testing purposes.

---

## 🍿 Tautulli


Stack is for **Tautulli**, a Python-based web application that monitors, analyzes, and tracks statistics for your Plex Media Server. It provides detailed insights into your media consumption and server activity.

---

## 🗄 Tiny Media Manager

Directory contains the Docker Compose setup for **Tiny Media Manager**. It's a media management tool used to organize and prepare your movie and TV show collections for media centers like Kodi or Plex, including fetching metadata and artwork.

---

## ✅ Uptime Kuma


Configuration deploys **Uptime Kuma**, a self-hosted monitoring tool like "Uptime Robot". It allows you to monitor the uptime of your services via HTTP(s), TCP, Ping, and more, with various notification options.

---

## 🔐 Vaultwarden


Stack is for **Vaultwarden**, an unofficial Bitwarden-compatible server written in Rust. It provides a lightweight and efficient solution for self-hosting your password manager, ensuring your sensitive data remains under your control.

---

## 💰 Wallos

Directory contains the Docker Compose setup for **Wallos**, a self-hosted personal finance management tool. It helps you track your expenses, income, and budgets, providing insights into your financial habits.

---

## 🔄 Watchtower

Configuration deploys **Watchtower**, a container that monitors your running Docker containers and automatically updates them to the latest available image when a new version is released. It helps keep your services up-to-date with minimal manual intervention.
