# micronaut-static-resource-issue

clone it

git checkout master
  
gradle run
  
curl http://localhost:10080/static/linked/hello.txt
 
expect: "hello softlink"
actual: Http Code 404 - Not Found

