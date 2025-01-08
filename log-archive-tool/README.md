# Log Archiver Tool

## Overview
A simple CLI tool to compress and archive logs, helping keep systems clean, organized, and efficient by saving storage space.

## Features
- Compress logs from a specified directory into a `.tar.gz` file.
- Save archives in a dedicated `archived_logs` directory.
- Log the archive operation date and time for reference.

## Benefits
- **Save Space**: Reduce disk usage by compressing old logs.
- **Stay Organized**: Keep logs archived and accessible.
- **Automate Cleanup**: Eliminate manual log management.

## Usage
Run the tool with the log directory as an argument:  
```bash
log-archive <log-directory>
