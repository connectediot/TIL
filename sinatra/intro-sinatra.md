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

- 시나트라 리로더

  - `gem install sinatra-contrib `

  - ```ruby
    #app.rb
    require "sinatra"
    require "sinatra/reloader"
    # 아래에 코드 계속
    ```

  - 