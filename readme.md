## remix-ide docker

docker load -i remix-ide.tar   
docker pull remixproject/remix-ide:latest  
docker run -p 8080:80 remixproject/remix-ide:latest    

Then go to http://localhost:8080 and you can use you Remix instance.

## 创建空分支

git checkout --orphan doc

git rm -rf .

