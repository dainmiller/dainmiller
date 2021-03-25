```ruby
doing_what_i_love = [:coding, :coaching]
dain.map(&:interests).filter do |interest| 
  return interest if interest == doing_what_i_love
end
```
