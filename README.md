# Magento RCE Exploit

This repository contains an improved and Python 3 compatible version of the Magento CE < 1.9.0.1 Post Auth Remote Code Execution (RCE) exploit. The script allows execution of arbitrary commands on the target server after successful authentication.

## Description

Magento CE versions below 1.9.0.1 are vulnerable to a post-authentication remote code execution exploit. This script, originally authored by @Ebrietas0, has been updated for compatibility with Python 3 and includes minor improvements for better usability and error handling.

## How to Use

1. Clone the repository:

    ```bash
    git clone https://github.com/Hakchoven/Magento-RCE.git
    ```

2. Navigate to the directory:

    ```bash
    cd Magento-RCE/
    ```

3. Run the script with the target URL and arbitrary command as an argument:

    ```bash
    python3 magento-rce-exploit.py http://example.com/index.php/admin/ "YOUR COMMAND"
    ```

Replace `example.com` with the target address.


## Disclaimer
This script is intended for educational purposes only. The author does not condone or support the use of this script for illegal or unethical activities. This script should only be used in legal security research or CTF environments. Use at your own risk.



---

Made by [Hackhoven](https://github.com/Hakchoven)
