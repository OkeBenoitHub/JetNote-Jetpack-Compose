# JetNote — Jetpack Compose

> **Course project.** Built while following an Android Jetpack Compose course (Udemy) — part of my Android learning path. My own products and case studies are on [okebenoithub.web.app](https://okebenoithub.web.app/en/).

A simple notes app: write a note, keep it, delete it when you're done.

## Features
- Add notes with a title and description.
- Notes persist locally with **Room**, including date and UUID type converters.
- Tap a note to remove it.

## Built with
Kotlin · Jetpack Compose · Hilt · Room · Coroutines + Flow · Material

## Architecture
MVVM with Hilt: the UI observes a `NoteViewModel` that collects a Room `Flow` through a repository.

## Run it
Open in Android Studio and run — no setup needed.

---

By **Benoit Presly Ndong Oke** — full-stack & mobile developer (Android · Web · Cloud).
Portfolio, case studies and CV: [okebenoithub.web.app](https://okebenoithub.web.app/en/) · [GitHub profile](https://github.com/OkeBenoitHub)
