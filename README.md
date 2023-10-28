# install and run

```
git clone git@github.com:CCS-Consulting-Cooperative/ccs-consulting-landing-page.git
cd ccs-consulting-landing-page
python -m http.server 8080
# or some other static directory serving helper
npx http-server -o ./public
```

# deploy

```
curl -sL https://firebase.tools | bash
firebase login
firebase deploy
```

- https://console.firebase.google.com/u/0/project/ccsconsulting-landing-page/settings/general
