<div align="center">

# 📜 Swift Basics: Protocols

**A concise, runnable Swift Playground exploring how protocols work.**

![Platform](https://img.shields.io/badge/Platform-iOS-lightgrey?style=flat-square)
![Swift](https://img.shields.io/badge/Swift-5-orange?style=flat-square&logo=swift)
![Playground](https://img.shields.io/badge/Xcode-Playground-blue?style=flat-square&logo=xcode)
![Stars](https://img.shields.io/github/stars/ahmetbostanciklioglu/Protocols?style=flat-square&color=6E48AA)
![Last Commit](https://img.shields.io/github/last-commit/ahmetbostanciklioglu/Protocols?style=flat-square&color=4776E6)

</div>

## 📖 Overview

Protocols in Swift define a blueprint of properties and methods that a conforming type must implement, enabling flexible, decoupled, and reusable code. This repository is a small, self-contained Xcode Playground (`Protocols.playground`) that demonstrates the core building blocks of Swift protocols through short, runnable examples. It is meant as a concise learning reference rather than a full application.

## 🧩 What it covers

- **Protocols as a parameter type** — declaring a protocol with a `{ get set }` property and passing any conforming value into a function.
- **Adopting protocol properties in structs** — `struct` types conforming to a protocol while adding their own extra properties.
- **Protocol inheritance** — one protocol (`TestModel`) inheriting the requirements of another (`Vehicle`).
- **Protocol methods** — declaring method requirements and composing multiple protocols through inheritance (`InheritedProtocol`).

## 🚀 Getting Started

```bash
git clone https://github.com/ahmetbostanciklioglu/Protocols.git
cd Protocols
```

Unzip `Protocols.playground.zip`, then open `Protocols.playground` in Xcode. The examples in `Contents.swift` run in the playground timeline.

## 📋 Requirements

- Xcode 12 or later
- Swift 5
- iOS playground target

## 🧑‍💻 Author

**Ahmet Bostancıklıoğlu** — [@ahmetbostanciklioglu](https://github.com/ahmetbostanciklioglu) · ahmetbostancikli@gmail.com

> ⭐ If this helped you, consider giving the repo a star!
