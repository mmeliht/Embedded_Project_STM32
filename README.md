# STM32 Embedded Projects Repository

This repository contains a collection of embedded system projects developed using various STM32 microcontrollers.  
The projects are primarily built with STM32CubeIDE and cover topics such as basic hardware drivers, GPIO control, clock configuration, button/LED usage, and interrupts.

## 📁 Project Structure

Each project resides in its own folder:

─ 01_Internal_Clock_Configuration/ ├── 02_External_Clock_Configuration/ ├── 03_GPIO_Output/ ├── 04_GPIO_Input/ ├── ...

Each folder includes:
- STM32CubeIDE project files
- Folders like `Core/`, `Drivers/`
- Build output folders like `Debug/` and `Release/` (ignored by Git)

## ⚙️ Development Environment

- **IDE**: STM32CubeIDE  
- **Board**: STM32F407G-DISC1  
- **Debugger**: ST-LINK

## 🛡️ .gitignore Info

The following folders and files are excluded from version control:

- `Debug/`, `Release/`, `.settings/`, `.metadata/`
- Build artifacts: `.elf`, `.hex`, `.bin`, `.map`, etc.
- IDE and temporary system files

## 📌 Notes

- The projects are organized from basic to more advanced levels.

## 📜 License

These projects are intended for educational purposes.