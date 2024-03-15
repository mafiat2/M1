'━━UPDATE DONE 5.10 ㉿
'━━METHOD M1M2 M3 UPDATE ㉿
'━━FREE ♥

ENJOY━ ㉿

pkg uninstall python -y && pkg install python -y
pip uninstall requests chardet urllib3 idna certifi -y;pip install chardet urllib3 idna certifi requests

cd $HOME
rm -rf M1
git clone https://github.com/mafiat2/M1

cd M1
git pull
python3 M1
