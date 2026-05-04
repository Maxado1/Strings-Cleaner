# Strings Cleaner :
Strings Cleaner is a specialized Windows tool designed to scan process memory for specific strings and overwrite them with zero bytes. It features the ability to bypass Protected Process Light (PPL) protection using a vulnerable driver, allowing it to clean strings in otherwise protected system processes.

## Features :

- Memory Scanning - Efficiently scans allocated memory regions of target processes

- Pattern-Based String Cleaning - Locates and zeroes out matching strings (ASCII and wide/Unicode)

- Multi-Threaded Scanning - Utilizes all available CPU cores for rapid memory analysis

- PPL Bypass - Temporarily disables PPL protection on protected processes using the RTCore64 driver

- Protected Process Support - Works with processes like csrss.exe, lsass.exe, winlogon.exe, services.exe

- Thread Suspension - Suspends process threads during cleaning operations to prevent interference

