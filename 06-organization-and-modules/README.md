URL TO GIT REPO IS: https://github.com/ffjabbari/TERRAFORM-002
FRED: 03- is one main.tf for everything.
FRED: 06- is when we create modules and then we ch to web-app and do the following commands.  Remember you have to enter two parameters at runtime which are passwords to DB which are at least 8 char and your pattern says 12121212
You do that, then you see four EC2's running and two sets of load balancers and two web-apps... Is really a great example...
0214  terraform init
10224  terraform plan -lock=false
10225  terraform deploy -lock=false
10226  terraform apply -lock=false
10227  terraform destroy
10228  terraform destroy -lock=false
10229  terraform apply
10230  terraform apply -lock=false
10231  history
10232  git status
10233  git add .
10234  git status
10235  git add .
10236  git status
10237  cd ..
10238  git status
10239  git add .
10240  git status
10241  git commit -ma"back to aa"
10242  git push origin head

