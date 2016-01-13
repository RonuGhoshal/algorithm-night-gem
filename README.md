# algorithm night

###How to use this:

In your Gemfile:
```ruby
gem 'algorithm-night'
```

or if you want to download to use in IRB:
```sh
$ gem install algorithm-night
$ irb
> require 'algorithm-night'
=> true
```

In IRB or your file you've had it in... you have the following structures/objects.

```ruby
stack  = Stack.new
queue  = Queue.new
linked = LinkedList.new
```

There are also some sorts, accessible via the Array class.

```ruby
a = [3,4,2,1,5]
a.bubble_sort     # sorted array
a.selection_sort  # sorted array
a.merge_sort      # sorted array
```


###WHAT STILL NEEDS TO BE DONE:
- Finishing Up Linked List
- Create Doubly Linked List
- Create Circular Linked List
- More sorts and searches
