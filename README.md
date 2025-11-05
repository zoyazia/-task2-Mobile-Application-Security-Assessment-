# -task2-Mobile-Application-Security-Assessment-
cybersecurity internship  task2 Mobile Application Security Assessment 
# 1️⃣ Update your system
sudo apt update && sudo apt upgrade -y

# 2️⃣ Install essential dependencies
sudo apt install -y git python3 python3-pip python3-venv

# 3️⃣ Clone MobSF from GitHub
cd /home/kali
git clone https://github.com/MobSF/Mobile-Security-Framework-MobSF.git
cd Mobile-Security-Framework-MobSF

# 4️⃣ Create a virtual environment
python3 -m venv venv

# 5️⃣ Activate the virtual environment
source venv/bin/activate

# 6️⃣ Upgrade pip & install all requirements
pip install --upgrade pip setuptools wheel
pip install -r requirements.txt

# 7️⃣ Run MobSF
./run.sh 127.0.0.1:8000

