Task: Vulnerability analysis and management (with ACS) Action: 
1. Automated Report Generation: Script to use the ACS API to generate vulnerability reports (e.g., CSV, PDF) for specific registries, clusters, or severity levels on a scheduled basis (e.g., weekly).
2.Automated Notification: Script to parse report data and automatically send summary emails or Slack messages to development and security teams listing new critical vulnerabilities.

Pre requities:

Make sure in your system you have below packages ready

sudo apt-get install -f
sudo apt-get clean
sudo apt-get update
sudo apt-get install -y libpangocairo-1.0-0 libpango-1.0-0 libcairo2 libffi-dev fonts-dejavu
sudo apt update
apt list --upgradable
sudo apt-get install -y python3-pip
pip3 install reportlab
pip3 install --upgrade pip --break-system-packages
pip3 install weasyprint pandas --break-system-packages
