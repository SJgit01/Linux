1. File Management

    List files in a directory: Displays files and directories in the current working directory.
        ls

    Copy files: Copies files or directories from one location to another.
        cp source destination

    Move/Rename files: Moves or renames files and directories.
        mv source destination

    Remove files: Deletes files or directories.
        rm file

    Create directories: Creates a new directory.
        mkdir directory_name

    Display current directory: Shows the current working directory.
        pwd

    View file content: Displays the content of a file.
        cat file_name

    Create an empty file or update a file's timestamp: Creates an empty file if it doesn't exist, or updates the timestamp of an existing file.
        touch file_name

2. File Permissions

    Change file permissions: Modifies the read, write, and execute permissions of a file or directory.
        chmod permissions file_name

    Change file ownership: Changes the ownership of a file or directory.
        chown user:group file_name

3. System Information

    Show system uptime: Displays how long the system has been running.
        uptime

    Check disk space usage: Shows available disk space on mounted file systems.
        df -h

    Display memory usage: Provides information about RAM and swap space.
        free -m

    Show system information: Displays detailed information about the system hardware and OS.
        uname -a

    Show system's IP address: Lists network interfaces and their IP addresses.
        ip addr

4. Process Management

    List running processes: Displays information about active processes.
        ps aux

    Monitor system processes in real-time: Provides a real-time view of system resource usage.
        top

    Kill a process by ID: Terminates a process with a specified process ID.
        kill PID

    Kill a process by name: Terminates processes by name.
        killall process_name

5. User Management

    Add a new user: Creates a new user account.
        adduser username

    Delete a user: Removes a user account and their home directory.
        deluser username

    Switch to another user: Allows switching to another user account.
        su username

6. Networking

    Ping a host: Sends ICMP echo requests to test network connectivity.
        ping host

    Display network connections: Shows active network connections and listening ports.
        netstat -tuln

    Download a file: Fetches a file from a URL using HTTP, HTTPS, or FTP.
        wget url

7. Archiving and Compression

    Create a tar archive: Combines multiple files into a single archive file.
        tar -cvf archive_name.tar directory_name

    Extract a tar archive: Extracts files from a tar archive.
        tar -xvf archive_name.tar

    Compress files using gzip: Compresses a file using the gzip algorithm.
        gzip file_name

8. Package Management (Debian-based Systems)

    Update package list: Refreshes the list of available packages.
        sudo apt update

    Upgrade installed packages: Upgrades all installed packages to the latest version.
        sudo apt upgrade

    Install a package: Installs a new software package.
        sudo apt install package_name

    Remove a package: Removes a software package.
        sudo apt remove package_name

9. Disk Management

    Check disk usage of a directory: Displays the size of a directory and its contents.
        du -sh directory_name

    Format a disk partition: Formats a partition with a specified file system.
        mkfs -t ext4 /dev/sdX1

    Mount a filesystem: Mounts a file system to a specified directory.
        mount /dev/sdX1 /mnt

10. Search and Filtering

    Search for files and directories: Locates files and directories based on a specified name.
        find /path -name file_name

    Search inside file contents: Finds patterns in file contents.
        grep "pattern" file_name

    Count lines, words, and characters in a file: Displays the number of lines, words, and characters in a file.
        wc file_name

11. Shell Scripting

    Define a variable: Assigns a value to a variable.
        variable_name=value

    For loop: Executes a series of commands repeatedly for a list of items.
        for i in {1..5}; do echo $i; done

12. File Transfers

    Transfer files between systems: Copies files securely between systems using SSH.
        scp source_file user@remote_host:/path/destination

    Synchronize files between systems: Synchronizes files and directories between two locations.
        rsync -avz source destination
