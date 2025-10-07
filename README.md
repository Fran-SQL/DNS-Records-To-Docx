> ⚠️ This script is designed for educational purposes. Use it at your own risk and always within the legal framework.

# DNS_records
Python project to gather DNS records from a domain and put them automatically into a docx file. 

## 🧠 Why?

Before using this script, the process of gathering these data was done manually, which was sometimes very time-consuming. This code allows us to automate the process, documenting the data in less than a minute.

## 🚀 Features

- Gather DNS records
- Export to docx

## 🛠️ Used technologies

- Python 3
- dnspython
- docx
- datetime

## ⚙️ How to use

Run the script, specify the domain to be analyzed, and a docx file with the results will be generated.

Maybe you need to install some libraries first. In that case you can use the requirements.txt file to do that:

```bash
pip install -r requirements.txt
```

Then you are ready to run the script:

```bash:
python dns_records_to_docx.py
```

The script will print a message, asking you to put the domain you want to analyze. Then you just have to write the domain and press enter. 
The script will generate a .docx file with the data gathered. For this example I wrote "github.com": 

```Enter the domain to analyze (e.g., example.com): github.com
Obtaining DNS records for github.com...
Document 'DNS_records_github_com.docx' successfully generated.
```

## Results
The generated .docx report will include the following information:
- **Report Title**: The title will feature the **domain analyzed**.
- **Timestamp**: The date and time when the DNS data was gathered.
- **DNS Records**: A structured listing of the following record types:
  - **A Records**
  - **MX Records**
  - **NS Records**
  - **TXT Records**

## ⚠️ Responsible use

This script has been designed for the purpose of **collecting public DNS information** and generating structured reports for **legitimate purposes of auditing, security analysis, research, or network administration**.

Please use this script ethically and responsibly.

* **Do not use this script for illegal or malicious activities,** including but not limited to, denial of service (DoS/DDoS) attacks, unauthorized port scanning, mass data collection for spam, or any other activity that may violate the privacy or security of third parties.
* **Be aware of the impact on third-party resources.** DNS queries, although they are public information, consume resources on DNS servers. Avoid making an excessive number of queries in a short period of time to the same domain or DNS server to avoid being perceived as abuse or an attack.
* **Respect the usage policies** of any DNS service or infrastructure you consult.
* **You are solely responsible** for the use you make of this tool and for any consequences arising from its application.

The author of this script is not responsible for any misuse of it.
