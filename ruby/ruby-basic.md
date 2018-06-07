# Ruby

### 0. 개요

1. 루비는 순수 객체 지향 언어이다
2. 모든것이 객체
3. Ruby on Rails 프레임 워크 등장으로 유명

### 1. puts vs print

```ruby
3.times { print "hello" } # => hellohellohello
3.times { puts "hello" } # => hello
						#	hello
						#   hello
```

> puts 는 개행문자 포함

### 3. p vs puts

```ruby
string = "hello"
puts string # hello => nil
p string # "hello" => "hello"
```

### 4. Naming conventions

- 변수
  - snake_case
- 상수
  - CONSTANT
- 클래스
  - CamelCase

### 5. pry

- 설치
  - `gem install pry`  
- 실행
  - `pry`

### 6. inline statement

```ruby
# if 문
puts "a=0" if a == 0 # "a=0"
puts "a=0" if a == 1 # 출력 안됨

# while 문
c = 0
result = c += 2 while c < 50
puts result # 50
    
puts "hi" if 0 #hi
# 0 은 true!!!!!!
```

### 7. case

```ruby
case name
when "chang2" then puts "hi chang2"  
when "tak" then puts "hi tak"  
else puts "hi"  
end
```

### 8. method

- 대부분의 언어

  - 클래스 밖 : function
  - 클래스 안 : method

- 루비에서는 모든 function은 method

- ```ruby
  # 루비에서의 method 선언
  def simple
  	puts "simple!!"
  end
  
  # 루비에서의 method는 괄호를 명시적으로 적어 줄 수 도 있습니다.
  def asdf()
  	puts "asdf"
  end  
  ```

- ``` ruby
  # 루비에서는 return이 없을때 마지막 연산 값을 return 합니다.
  def add2(a,b)
  	a+b
  end  
  
  add2(1,2) # => 3
  
  # return을 선택적을 사용할 수 있습니다.
  def divide(a,b)
  	return "I don't think so" if b == 0
  	a / b
  end
  ```

- 

