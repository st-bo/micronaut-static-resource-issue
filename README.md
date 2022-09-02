# micronaut-static-resource-issue

  clone it
  gradle run
  curl http://localhost:10080/static/linked/hello.txt
 
expect: "hello softlink"
actual: Http Code 404 - Not Found

