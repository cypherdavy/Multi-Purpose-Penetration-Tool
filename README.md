
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multi-Purpose Penetration Tool (MPPT)</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
        h1, h2 {
            color: #4a86e8;
        }
        h1 > span {
            color: #333;
            font-size: 1.25em;
            font-weight: normal;
        }
        h2 > span {
            color: #333;
            font-size: 1.1em;
            font-weight: normal;
        }
        a {
            color: #4a86e8;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1><span>Multi-Purpose Penetration Tool</span> (MPPT) <span>- v1.0.0</span></h1>

    <p>This tool is designed for educational and legitimate penetration testing purposes only. Copying, modifying, or redistributing this tool without explicit permission is strictly prohibited. The developer assumes no responsibility for any misuse of this tool. Always ensure you have proper authorization before testing any system.</p>


    <p>To deter copying, this README.md file includes a custom watermark and a notice. The code itself has been obfuscated using Pyarmor. If you wish to use this tool for legitimate purposes, please contact <a href="mailto:your_email@example.com">your_email@example.com</a> to request permission.</p>

    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#features">Features</a></li>
        <li><a href="#requirements">Requirements</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#platforms">Platforms</a></li>
        <li><a href="#disclaimer">Disclaimer</a></li>
        <li><a href="#license">License</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>

    <h2 id="features">Features</h2>
    <ul>
        <li>Scanning for open ports using Nmap</li>
        <li>Finding known vulnerabilities using a database like VulDB or CVE</li>
        <li>Implementing exploits for specific vulnerabilities</li>
        <li>Bruteforcing credential login functionality</li>
    </ul>

    <h2 id="requirements">Requirements</h2>
    <ul>
        <li>Python 3.x</li>
        <li><a href="https://pypi.org/project/requests/">requests</a> library: <code>pip install requests</code></li>
        <li><a href="https://pypi.org/project/colorama/">colorama</a> library: <code>pip install colorama</code></li>
    </ul>

    <h2 id="installation">Installation</h2>
    <h3>Parrot Security OS/Kali Linux</h3>
    <ol>
        <li>Transfer the file to your Parrot/Kali Linux system using SCP (Secure Copy).</li>
        <li>Install the required libraries:</li>
        <pre><code>sudo apt-get update
sudo apt-get install -y python3-pip
sudo pip3 install requests colorama
        </code></pre>
        <li>Run the tool by providing the target URL:</li>
        <pre><code>python3 mppt.py <target_url></code></pre>
    </ol>

    <h3>Termux</h3>
    <ol>
        <li>Transfer the file to your Termux system using SCP or copy-paste it into the Termux terminal.</li>
        <li>Install the required libraries:</li>
        <pre><code>pkg update
pkg install python
pip install requests colorama
        </code></pre>
        <li>Run the tool by providing the target URL:</li>
        <pre><code>python mppt.py <target_url></code></pre>
    </ol>

    <h3>Windows</h3>
    <ol>
        <li>Install Python on your Windows system: <a href="https://www.python.org/downloads/windows/">Python Downloads</a></li>
        <li>Transfer the file to your Windows system or create a new Python file and paste the updated code into it.</li>
        <li>Install the required libraries:</li>
        <pre><code>pip install requests colorama
        </code></pre>
        <li>Run the tool by providing the target URL:</li>
        <pre><code>python mppt.py <target_url></code></pre>
    </ol>

    <h2 id="usage">Usage</h2>
    <p>To run the tool, simply provide the target URL as an argument:</p>
    <pre><code>python mppt.py <target_url></code></pre>
    <p>Replace <code><target_url></code> with the URL of the target you want to test.</p>

    <h2 id="platforms">Platforms</h2>
    <ul>
        <li>Parrot Security OS</li>
        <li>Kali Linux</li>
        <li>Termux</li>
        <li>Windows</li>
    </ul>

    <h2 id="disclaimer">Disclaimer</h2>
    <p>
        <em>
            Please note that this tool is intended for educational and legitimate penetration testing purposes only. Using the MPPT for illegal activities is strictly prohibited. The developer assumes no responsibility for any misuse of this tool. Always ensure you have proper authorization before testing any system.
        </em>
    </p>

    <h2 id="license">License</h2>
    <p>
        <em>
            This project is licensed under a custom license that forbids copying or modification without explicit permission. For more information, please contact <a href="mailto:your_email@example.com">your_email@example.com</a>.
        </em>
    </p>

    <h2 id="contact">Contact</h2>
    <p>
        <em>
            For questions, concerns, or suggestions, please contact <a href="mailto:your_email@example.com">your_email@example.com</a>.
        </em>
    </p>
</body>
</html>
