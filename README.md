Activate env
    myvenv\Scripts\activate

Run the app
    python -m flask run



We can create rules.tsv file to defines the rules that ZAP should follow during the scan

# Example rules.tsv
ID    Name    Enabled    Risk    Description
1000  SQL Injection - MySQL    true    High    Looks for SQL Injection vulnerabilities specific to MySQL databases
1001  SQL Injection - Oracle   true    High    Looks for SQL Injection vulnerabilities specific to Oracle databases

