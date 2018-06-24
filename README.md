# isaax46


isaaxで動かす
sudo systemctl disable yorobled
sudo systemctl enable isaax-project
sudo systemctl enable isaaxd


今までのデーモンで動かす
sudo systemctl enable yorobled
sudo systemctl stop isaax-project
sudo systemctl stop isaaxd
sudo systemctl disable isaax-project
sudo systemctl disable isaaxd
sudo systemctl status isaax-project
sudo systemctl status isaaxd
sudo systemctl status yorobled
