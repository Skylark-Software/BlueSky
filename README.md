# BlueSky - Life Management Tools

A sovereign-cloud alternative to NextCloud — self-hosted or cloud-hosted, with zero footprint on your devices.

## Overview

BlueSky is a self-hosted personal productivity platform with 18 integrated modules covering tasks, email, calendar, documents, photos, recipes, finance, health tracking, security, and more.

## Key Features

- **Self-hosted sovereignty** — deploy with Docker, HTTPS reverse proxy, and Tailscale. Your data never leaves your infrastructure
- **Zero-footprint web client** — works on any device including mobile. Delete the bookmark and nothing exists on your phone
- **Native desktop client** — Qt6/C++ cross-platform app for Linux, Windows, and macOS. Swift for Apple coming soon
- **18 modules** — Tabula (tasks), Epistula (email), Vitae (health), Pecunia (finance), Imago (photos), Bibliotheca (books), Culina (recipes), Archivum (documents), Officina (office suite), Praesidium (security), Cognitio (AI), Spectacula (media), Portae (remote access), Tempestas (weather), and more

## Architecture

- **Backend**: FastAPI + PostgreSQL + Docker
- **Web Client**: HTMX + Jinja2 with dark theme
- **Desktop Client**: Qt6 / QML / C++20
- **Office Integration**: Collabora Online (LibreOffice), Microsoft 365, Google Workspace
- **Email**: Full IMAP client with smart views, unified inbox, threading, and WebSocket real-time updates

## Status

In active development. Not yet open source.

## License

Copyright 2025-2026 Skylark Software LLC. All Rights Reserved.
