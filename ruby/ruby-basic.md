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



