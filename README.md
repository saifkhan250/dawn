B1: setup
git clone https://github.com/saifkhan250/dawn.git

accounts.yaml

  - email: "account1@example.com"      
    token: "example_token_1"           
  - email: "account2@example.com" 
    token: "example_token_2"
 
proxy.yaml

proxies: 
  - "proxy1:port"                      
  - "proxy2:port"     
 
B2: Lệnh 

pip install -r requirements.txt

python main.py
