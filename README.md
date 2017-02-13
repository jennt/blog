# Blog


## Synopsis
Tutorial taken from http://guides.rubyonrails.org/getting_started.html


## Code Example
```ruby
class Article < ApplicationRecord
  has_many :comments
  validates :title, presence: true,    
  length: { minimum: 3 }
end  

  ```

## Motivation
To practice making Rails apps.


<!-- ```ruby
``` -->

## Authors
* Jenn Tustin
