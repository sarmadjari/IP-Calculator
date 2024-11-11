# CIDR Calculator

A simple personal tool to calculate the minimal-size CIDR block that covers a specified IP range or a starting IP and the number of IPs. This calculator helps you quickly determine the appropriate CIDR notation for your network planning and subnetting tasks.

## Features

- **Single CIDR Output**:
  - Calculates the smallest possible CIDR block that encompasses all the specified IP addresses.
  - Provides a single CIDR notation, even if it includes additional IP addresses beyond your specified range.

- **Two Input Methods**:
  - **IP Range**: Enter a start IP and an end IP to calculate the CIDR block that covers the entire range.
  - **Start IP and Number of IPs**: Provide a starting IP and specify the number of IPs needed.

- **User-Friendly Interface**:
  - Simple and intuitive design for ease of use.
  - Provides immediate results and helpful error messages for invalid inputs.

## How It Works

1. **Select Input Method**:
   - Choose between **"IP Range"** or **"Start IP and Number of IPs"**.

2. **Enter IP Information**:
   - **For IP Range**:
     - Enter the **Start IP** and **End IP** of your desired range.
   - **For Start IP and Number of IPs**:
     - Enter the **Start IP** and the **Number of IPs** you need.

3. **Calculate CIDR**:
   - Click the **"Calculate CIDR"** button.

4. **View Results**:
   - The calculator displays the minimal-size CIDR block that covers your specified IP addresses.

## Example Usage

### Example 1: IP Range

- **Input**:
  - Start IP: `192.168.1.100`
  - End IP: `192.168.1.200`
- **Output**:
  - `192.168.1.0/24` (Covers 256 IPs)

### Example 2: Start IP and Number of IPs

- **Input**:
  - Start IP: `10.0.0.0`
  - Number of IPs: `500`
- **Output**:
  - `10.0.0.0/22` (Covers 1024 IPs)
