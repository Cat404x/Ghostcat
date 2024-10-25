
# Ghostcat

Ghostcat is a basic 
cybersecurity tool designed for network 
scanning and connection monitoring. 
It uses ARP requests to discover devices on 
the network and sets up a simple server 
to detect incoming connection attempts.

## Features
- **Network Scanning**: Uses ARP requests to discover devices on a specified IP range.
- **Connection Monitoring**: Monitors a specified port for incoming connection attempts.
- **Logging**: Records activities and findings to a log file.

## Installation
To run this script, you'll need to install the Scapy library. You can install it using pip:
```sh
pip install scapy


1. **Clone the repository**:
   ```sh
   git clone https://github.com/Cat404x/Ghostcat.git
   cd Ghostcat
   ```

2. **Create or update the script**:
   Create a new file or update the existing file `ghost_cat.py` with the corrected script.

3. **Stage the changes**:
   ```sh
   git add ghost_cat.py
   ```

4. **Commit the changes**:
   ```sh
   git commit -m "Fix Ghost Cat script"
   ```

5. **Push the changes**:
   ```sh
   git push origin main
   ```
Certainly! I'd be happy to provide you with the commands to run the "Ghost Cat" cybersecurity tool script. Here's a step-by-step guide:

1. First, ensure you have Python installed on your system. The script is written in Python and requires Python 3.x.

2. Install the required library (Scapy) if you haven't already:
   ```
   pip install scapy
   ```

3. Save the Python script to a file, for example, `ghost_cat.py`.

4. Open a terminal or command prompt and navigate to the directory containing the script.

5. To run the script, use the following command:
   ```
   python ghost_cat.py
   ```

6. Once the script is running, you'll see a menu with options. Here's how to use each option:

   - To scan a network:
     Enter '1' when prompted, then input an IP range like '192.168.1.0/24'

   - To monitor connections:
     Enter '2' when prompted, then input a port number to monitor

   - To exit the program:
     Enter '3'

7. For the enhanced version with command-line arguments:

   - To scan a network:
     ```
     python ghost_cat.py -s 192.168.1.0/24
     ```

   - To monitor a specific port:
     ```
     python ghost_cat.py -m 8080
     ```

   - To sniff network traffic on a specific interface:
     ```
     python ghost_cat.py -i eth0
     ```

   - To see all available options:
     ```
     python ghost_cat.py -h
     ```

Remember, you may need to run the script with administrator/root privileges for some operations, especially network scanning and packet sniffing. On Unix-like systems, you can use `sudo`:

```
sudo python ghost_cat.py
```

Always ensure you have the necessary permissions and are complying with all relevant laws and regulations when using this tool. It should only be used on networks and systems you own or have explicit permission to test.


