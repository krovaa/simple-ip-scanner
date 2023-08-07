# Simple IP Scanner

Simple IP Scanner is a C# console application that allows users to scan a range of IP addresses to find responsive hosts on a local network. The tool uses asynchronous tasks to perform parallel pings on the specified IP range, providing quick and efficient scanning.

## Features

- Scans a user-specified IP range or predefined default IP ranges.
- Uses asynchronous tasks for parallel pings, making the scanning process faster.
- Retrieves the host name of the responsive IP addresses using DNS resolution.
- Displays the list of responsive IP addresses along with their corresponding host names (if available).
- Calculates and displays the percentage of IP addresses that are responsive within the scanned range.
- Suggests a random non-responsive IP address if any are available in the scanned range.

## How to Use

1. When running the application, the user will be prompted to either enter a custom IP range or press Enter to use the default IP ranges.
2. The scanner will then attempt to ping all IP addresses within the specified range.
3. Responsive IP addresses will be listed along with their host names (if available).
4. The percentage of responsive IPs within the range will be displayed.
5. If there are responsive IP addresses available, the tool will suggest a random address that is not being used.
6. The process can be repeated for multiple IP ranges.
7. The scanning progress will be shown for each range and will indicate when the scan is completed.

## Dependencies

The application uses the following namespaces from the .NET framework:

- System
- System.Collections.Generic
- System.Linq
- System.Net.NetworkInformation
- System.Threading
- System.Threading.Tasks