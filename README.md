# Cypher

Cypher is a Python-based project designed to detect vulnerabilities in websites using a variety of security tools. It leverages tools like nmap, nikto, dnsrecon, uniscan, theHarvester, sslyze, fierce, load balance detector, and amass to perform comprehensive security assessments and identify potential threats.

## Features

- **Nmap**: Network exploration tool and security/port scanner.
- **Nikto**: Web server scanner which performs comprehensive tests against web servers.
- **DNSRecon**: DNS reconnaissance tool.
- **Uniscan**: Web vulnerability scanner.
- **theHarvester**: E-mail, subdomain, and people names harvester.
- **SSLyze**: Fast and powerful SSL/TLS scanning library.
- **Fierce**: DNS reconnaissance tool for finding non-contiguous IP space.
- **Load Balance Detector**: Detects load-balanced web servers.
- **Amass**: In-depth DNS enumeration and network mapping tool.

## Installation

To set up and run the Cypher project, follow these steps:

### Prerequisites

- Ensure you have Python installed on your system. You can download it from [Python's official website](https://www.python.org/downloads/).
- Install the required security tools:
  - nmap: [Installation Guide](https://nmap.org/book/inst-windows.html)
  - nikto: [Installation Guide](https://github.com/sullo/nikto)
  - dnsrecon: [Installation Guide](https://github.com/darkoperator/dnsrecon)
  - uniscan: [Installation Guide](https://github.com/poison0x/Uniscan)
  - theHarvester: [Installation Guide](https://github.com/laramies/theHarvester)
  - sslyze: [Installation Guide](https://github.com/nabla-c0d3/sslyze)
  - fierce: [Installation Guide](https://github.com/mschwager/fierce)
  - load balance detector: [Installation Guide](https://github.com/Edu4rdSHL/load_balancer_detector)
  - amass: [Installation Guide](https://github.com/OWASP/Amass)

### Steps

1. **Clone the Repository**: Clone the project repository to your local machine.
    ```sh
    git clone <https://github.com/daharaboi/Cypher>
    ```

2. **Navigate to the Directory**: Use the `cd` command to navigate to the `cypher` directory:
    ```sh
    cd path/to/cypher
    ```

3. **Run the Script**: Execute the main script to start the vulnerability assessment:
    ```sh
    python cypher.py
    ```

## Understanding Threat Levels

Cypher classifies vulnerabilities into three categories based on their severity:

- **Low**: Minor issues that do not pose an immediate threat but should be addressed to enhance security.
- **Moderate**: Vulnerabilities that could be exploited under certain conditions. These should be fixed promptly.
- **High**: Critical vulnerabilities that pose a significant risk to the security of the website. Immediate action is required to mitigate these threats.

## Remedies for Vulnerabilities

For each detected vulnerability, Cypher provides suggestions on how to remediate the issue. Below are some common remedies:

- **Update Software**: Ensure all software, including web servers, frameworks, and libraries, are up to date with the latest security patches.
- **Implement Firewalls**: Use Web Application Firewalls (WAFs) to protect against common attacks such as SQL injection and cross-site scripting (XSS).
- **Harden Configurations**: Secure server and application configurations to minimize the attack surface.
- **Regular Audits**: Conduct regular security audits and vulnerability assessments to identify and address new threats.
- **Input Validation**: Implement robust input validation to prevent injection attacks and other forms of data manipulation.

## File Structure

The directory structure of the project should look like this:

```
cypher/
│
├── cypher.py
├── README.md
│
```
