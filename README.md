# USB

Update the node and server code using git and a USB Flash Drive

## Initial Setup

1. Insert a USB flash drive into your PC
2. Open the root directory of the USB flash drive in Command Prompt, PowerShell, Terminal, etc.
3. Clone and cd into this repository using the following command:

    ```bash
    git clone https://github.com/Wireless-Communication-System/USB.git
    cd USB

    ```

4. Clone the Server and Node repositories by running ```Create.cmd``` or by manually running the following commands:

    ```bash
    cd Update
    git clone https://github.com/Wireless-Communication-System/Server.git
    git clone https://github.com/Wireless-Communication-System/Node.git

    ```

5. Close the command line window
6. Eject the USB flash drive

## Updating using the CMD

- Click on ```Update.cmd```

## Updating Manually

1. Open the root directory of the USB flash drive in Command Prompt, PowerShell, Terminal, etc.
2. Run the following commands:

    ```bash
    cd USB
    cd Update
    cd Server
    git pull
    cd ..
    cd Node
    git pull

    ```

3. Close the command line window

## Updating a Node or Server Device

1. Turn off the Node or Server
2. Insert the USB flash drive into the device
3. Turn on the device
4. Wait for the device's program to start
5. Unplug the USB flash drive
