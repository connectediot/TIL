# intro-sinatra

- `mkdir sinatra-test`

- `cd sinatra-test`

- `touch app.rb`

- `gem install sinatra`

- ```ruby
  # app.rb
  require 'sinatra'
  
  get '/' do
    'Hello world!'
  end
  ```

- `ruby app.rb -o $IP`

