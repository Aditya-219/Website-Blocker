# Website Blocker

A simple Python script to block specified websites during a specified time range by manipulating the hosts file.

## Overview

This project allows you to block access to specific websites on your computer during a specified time period. It modifies the hosts file, redirecting specified websites to the loopback address (127.0.0.1) to restrict access.

## Usage

1. Modify the `website_list` variable in the script to include the URLs of the websites you want to block.
2. Set the `start_date` and `end_date` to define the time range during which the blocking should take effect.
3. Run the script as an administrator to apply the changes to the hosts file.

## Requirements

- Python 3.x

## Usage Example

```bash
python website_blocker.py
```

## Important Note

Make sure to run the script with administrator privileges to allow modifications to the hosts file.

## Acknowledgments

Inspired by the need for a distraction-free work environment.
