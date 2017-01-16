Welcome to my site, I'm an App Sec Engineer at Appfolio. I use this to post
about security research that I do on my own time.

Main _interests_ involve dynamic code analysis, and applying my undergrad
computer science theory to the computer security problem domain.

Main _efforts_ include developing a ruby script that can be required into any
other ruby program that will report any vulnerabilities present in the loaded
classes. I'll use this in security assessments as a complement to static code
analysis with [brakeman](http://brakemanscanner.org/){:target="_blank"}.


```ruby
def []= key, val
  instance_eval "@#{key}=\"#{val}\""
end
```
