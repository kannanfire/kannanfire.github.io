HELLO

Whenever we make changes to the notebook, we run this and then
``` 	
jupyter nbconvert --to html final_project.ipynb 
```

this allows us to check one .ipbyn file and then convert it its own html file
we then call
``` 
mv <our file>.html index.html 
```
once changes are made and index.html updated
we run these to allow kannanfire.github.io 

``` 
git add <files>
git commit -m "you know this already"
git push 
```

