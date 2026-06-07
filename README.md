# Ransomware Detection System

## About
A real-time file system monitoring tool for early detection of ransomware attacks using Python.

## Technologies Used
- Python
- Watchdog Library (file system monitoring)
- Hashlib (SHA256 cryptographic hashing)

## How It Works
1. Monitors a specified directory continuously in real-time
2. Detects file creation, modification and deletion events
3. Computes SHA256 hash of each affected file
4. Logs all events with timestamp, file path and hash value
5. Helps identify ransomware activity before widespread damage occurs

## Sample Output
