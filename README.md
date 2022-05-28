Tested with Ubuntu server 21.10

## 1. Install Tor
sudo apt-get install tor

## 2. Create 2 alternate torrc files
sudo nano /etc/tor/torrc.slow

sudo nano /etc/tor/torrc.fast

## 3. Create 2 bash files to be execute by crontab
 nano torcron.slow
 
 chmod +x torcron.slow
 
 nano torcron.fast
 
 chmod +x torcron.fast
 
## 4. Edit crontab 
 sudo crontab
