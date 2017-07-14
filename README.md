
# Test2
##Base64 encryption method 
This calls the Base64 method and encrypts a user-provided string

Pretty humdrum, more to come soon! 

```Ruby

#!/bin/bash/ruby

require "base64"
puts "hello there, please give me a string to encrypt..."
user_input =  gets.chomp
string = Base64.encode64(user_input)
puts string
puts "neat.."
puts "now let's change it back "
puts "paste the code back into the prompt please" 
new_input = gets.chomp 
newstring = Base64.decode64(new_input)
puts newstring
```


...Perhaps not earth-shattering, but you're learning .md files well ;)
