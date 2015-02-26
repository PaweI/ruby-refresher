####Week 7 Challenge at Makers Academy!

####SYNOPSIS

Refreshing Ruby as a collection of tests to solve various of tasks.
Try to write as many lines of code as possible.

####MY APPROACH

Firstly I was trying to do all tasks by using knowledge I got already. But I end up with some methods with more than 2 lines. So In order to make my code more efficient I had to look at Ruby documentation where I found some neat methods which cover my Ruby knowledge gaps. 

####TECHNOLOGIES:

- *Ruby*

- *Rspec*

####HOW TO RUN

As this a refresher, you can check my passing tests by running in you terminal

```
rspec
```

####CODE SNIPPET

My results:

![alt tag](https://github.com/PaweI/ruby-refresher/blob/master/public/results.png)

####WHAT I'VE LEARNT

There is always ways to refactor your code. Like:

```ruby
def all_elements_except_first_3(array)
  3.times { array.shift }
  array
end
```

can become:

```ruby
def all_elements_except_first_3(array)
  array.drop(3)
end
```


####FUTURE IMPROVEMENTS

I would like to finish last task, which is to write method returning song "99 bottles of bear"



