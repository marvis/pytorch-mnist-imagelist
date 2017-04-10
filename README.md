#### version 0.2
Add list dataset

Usage:
- find folder/train/ -name "*.png" | awk -F / '{print $0, $3}' | tee train.txt
-  find folder/test/ -name "*.png" | awk -F / '{print $0, $3}' | tee test.txt
- python main.py

#### version 0.1
Support both online dataset and folder dataset

modify data_from to 0 or 1

#### version 0.0
Test ImageFolder dataloader

Usage:
- unzip folder.tar.gz
- python main.py
