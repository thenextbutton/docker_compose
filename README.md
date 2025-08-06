# 🐳 Docker Compose Stacks
[![Docker Compose](https://img.shields.io/badge/Docker-Compose-2496ED?logo=docker&logoColor=white)](https://docs.docker.com/compose/)
[![Language: YAML](https://img.shields.io/badge/Language-YAML-cb171e?logo=yaml&logoColor=white)](https://yaml.org/)
[![GitHub last commit](https://img.shields.io/github/last-commit/thenextbutton/docker_compose)](https://github.com/thenextbutton/docker_compose/commits/main)
[![GitHub Issues](https://img.shields.io/github/issues/thenextbutton/docker_compose)](https://github.com/thenextbutton/docker_compose/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/thenextbutton/docker_compose)](https://github.com/thenextbutton/docker_compose/pulls)
[![GitHub Stars](https://img.shields.io/github/stars/thenextbutton/docker_compose?style=social)](https://github.com/thenextbutton/docker_compose/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/thenextbutton/docker_compose/blob/main/LICENSE)

---

These are my personal Docker Compose configurations for self-hosted applications and services. Each subdirectory holds a distinct stack, helping me remember how to deploy and manage them.

---

## 📋 Table of Contents

* [🏠 AdGuard Home Sync](#-adguard-home-sync)
* [📚 Audiobookshelf](#-audiobookshelf)
* [🌐 DDNS Updater](#-ddns-updater)
* [📹 Frigate](#-frigate)
* [💚 Gatus](#-gatus)
* [📊 Glances](#-glances)
* [🚀 Homepage](#-homepage)
* [🖼 Koillection](#-koillection)
* [▶ MeTube](#-metube)
* [🚨 NetAlertX](#-netalertx)
* [⚙ Nginx Proxy Manager](#-nginx-proxy-manager)
* [🔔 Ntfy](#-ntfy)
* [⏰ NTP](#-ntp)
* [⚡ Speedtest Tracker](#-speedtest-tracker)
* [📄 Static Web Server](#-static-web-server)
* [🍿 Tautulli](#-tautulli)
* [🗄 Tiny Media Manager](#-tiny-media-manager)
* [✅ Uptime Kuma](#-uptime-kuma)
* [🔐 Vaultwarden](#-vaultwarden)
* [💰 Wallos](#-wallos)
* [🔄 Watchtower](#-watchtower)

---

## 🏠 [AdGuard Home Sync](https://github.com/thenextbutton/docker_compose/tree/main/adguardhome-sync)

This stack is for **syncing AdGuard Home configurations** between instances. Helps keep my ad-blocking rules consistent everywhere.

---

## 📚 [Audiobookshelf](https://github.com/thenextbutton/docker_compose/tree/main/audiobookshelf)


My Docker Compose setup for **Audiobookshelf**, a self-hosted server for audiobooks and podcasts. Lets me organize and stream my audio content.

---

## 🌐 [DDNS Updater](https://github.com/thenextbutton/docker_compose/tree/main/ddns-updater)

This deploys my **Dynamic DNS (DDNS) updater**. It automatically updates my domain's IP so services stay accessible even if my home IP changes.

---

## 📹 [Frigate](https://github.com/thenextbutton/docker_compose/tree/main/frigate)


This stack is for **Frigate**, my NVR with AI object detection. It uses a Coral TPU to process camera feeds, detect objects, and trigger recordings/notifications.

---

## 💚 [Gatus](https://github.com/thenextbutton/docker_compose/tree/main/gatus)

My Docker Compose setup for **Gatus**, my health dashboard. I use it to monitor the status and uptime of my services and get alerts.

---

## 📊 [Glances](https://github.com/thenextbutton/docker_compose/tree/main/glances)


This runs **Glances**, my system monitoring tool. It gives me a quick overview of server resources: CPU, RAM, disk, network, and processes.

---

## 🚀 [Homepage](https://github.com/thenextbutton/docker_compose/tree/main/homepage)

This stack sets up my customizable **homepage** for self-hosted services. It's my central dashboard for quick access and information.

---

## 🖼 [Koillection](https://github.com/thenextbutton/docker_compose/tree/main/koillection)

My Docker Compose setup for **Koillection**, my collection management tool. I use it to organize and catalog my physical and digital collections.

---

## ▶ [MeTube](https://github.com/thenextbutton/docker_compose/tree/main/metube)


This deploys **MeTube**, a web GUI for `yt-dlp`. I use it to easily download videos and audio from various platforms.

---

## 🚨 [NetAlertX](https://github.com/thenextbutton/docker_compose/tree/main/netalertx)

This stack is for **NetAlertX**, my network monitoring and alerting tool. It helps me track network devices, detect new ones, and get alerts for changes.

---

## ⚙ [Nginx Proxy Manager](https://github.com/thenextbutton/docker_compose/tree/main/nginx-proxy-manager)


My Docker Compose setup for **Nginx Proxy Manager**. I use it for easy Nginx proxy host management and free Let's Encrypt SSL certificates.

---

## 🔔 [Ntfy](https://github.com/thenextbutton/docker_compose/tree/main/ntfy)

This deploys **Ntfy**, my simple HTTP-based push notification service. I use it to send push notifications to my phone/desktop from scripts.

---

## ⏰ [NTP](https://github.com/thenextbutton/docker_compose/tree/main/ntp)

This stack sets up a local **NTP (Network Time Protocol) server**. Handy for accurate time sync across my local network devices.

---

## ⚡ [Speedtest Tracker](https://github.com/thenextbutton/docker_compose/tree/main/speedtest-tracker)

My Docker Compose setup for **Speedtest Tracker**. It runs periodic speed tests and logs results, helping me monitor my internet performance.

---

## 📄 [Static Web Server](https://github.com/thenextbutton/docker_compose/tree/main/static-web-server)

This configuration provides a simple **static web server**. I use it for hosting basic HTML/CSS/JS files or quick testing.

---

## 🍿 [Tautulli](https://github.com/thenextbutton/docker_compose/tree/main/tautulli)


This stack is for **Tautulli**, my Plex Media Server monitor. It tracks and analyzes statistics for my Plex activity.

---

## 🗄 [Tiny Media Manager](https://github.com/thenextbutton/docker_compose/tree/main/tiny_media_manager)

My Docker Compose setup for **Tiny Media Manager**. I use it to organize and prepare my movie/TV show collections for media centers.

---

## ✅ [Uptime Kuma](https://github.com/thenextbutton/docker_compose/tree/main/uptime-kuma)


This deploys **Uptime Kuma**, my self-hosted monitoring tool. I use it to check the uptime of my services via HTTP(s), TCP, Ping, etc., with notifications.

---

## 🔐 [Vaultwarden](https://github.com/thenextbutton/docker_compose/tree/main/vaultwarden)


This stack is for **Vaultwarden**, my unofficial Bitwarden-compatible server. It's my lightweight solution for self-hosting my password manager.

---

## 💰 [Wallos](https://github.com/thenextbutton/docker_compose/tree/main/wallos)

My Docker Compose setup for **Wallos**, a self-hosted personal finance management tool. I use it to track expenses, income, and budgets.

---

## 🔄 [Watchtower](https://github.com/thenextbutton/docker_compose/tree/main/watchtower)

This configuration deploys **Watchtower**, a container that automatically updates my other running Docker containers to their latest images. Keeps things fresh.
