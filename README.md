git clone https://github.com/<username>/<repo>.git
cd <repo>
git config user.name "georgechaos1"
git config user.email "<το verified email σου στο GitHub>"
echo 'print("Hello Base via CLI")' > hello_cli.py
git add hello_cli.py
git commit -m "valid code commit for Base quest"
git push origin main
