# tools-installations
<details><summary>Recon</summary></details>
<details>
  <summary>XSS Tools</summary>
  
  # XSStrike
  
  ### Installations
  
  ```
  sudo mkdir -p /opt/xss
  cd /opt/xss/
  sudo git clone https://github.com/s0md3v/XSStrike.git
  cd XSStrike
  pip3 install -r requirements.txt
  sudo chmod +x xsstrike.py
  cd
  sudo ln -sf /opt/xss/XSStrike/xsstrike.py /usr/local/bin/xsstrike
  xsstrike -h
  ```
</details>
