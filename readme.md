Git course
112
153
this is branch bug
https://catalog.us-east-1.prod.workshops.aws/event/dashboard/en-US

mkdir anycompany-crm && cd anycompany-crm
unzip ~/Downloads/crm-app.zip
cp -R crm-app/. .
rm -rf crm-app
git init
git add -A
git commit -m "Initial CRM application"
git remote add origin https://github.com/YOUR_ACCOUNT/YOUR_REPO.git
git branch -M main
git push -u origin main
