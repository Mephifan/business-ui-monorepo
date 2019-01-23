# Business ui monorepo 



**a demo how it works**

```
1. npm install --global lerna
2. after 'lerna init --independent' we get a packages folder
3. we put all our basis components in this monorepo under /packages
4. we generate package.json for each packages with a init version
5. with 'lerna add xxx --scope=yyy' will dependece yyy->xxx be added
6. generate symlinks for packages with 'lerna bootstrap' 
7. with 'lerna publish' publish the repo
```

