Usage:
- unzip folder.tar.gz
- find folder/train/ -name "*.png" | awk -F / '{print $0, $3}' | tee train.txt
- find folder/test/ -name "*.png" | awk -F / '{print $0, $3}' | tee test.txt
- python main.py
