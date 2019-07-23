# Object oriented programming
## Definition
  Object-oriented programming (OOP) is a programming paradigm based on the concept of "objects", which can contain data, in the form of fields (often known as attributes), and code, in the form of procedures (often known as methods). [Wikipedia](https://en.wikipedia.org/wiki/Object-oriented_programming)
## Examples
### C++

```c++
//
// File Geek.h
//

#include <bits/stdc++.h> 
using namespace std; 

class Geek 
{ 
  public: 
	string geekname; 

	void printname() 
	{ 
	  cout << "Geekname is: " << geekname; 
	} 
}; 

//
// File main.cpp
//

#include <Geek.h> 

int main() { 
	Geek obj1; 

	obj1.geekname = "Neo"; 

	obj1.printname(); 

  return 0; 
} 
```

### Python
```python

# File geek.py

class Geek():
    
  def __init__(self,name: str=None):
    self.geekname = name

  def printname(self):
    print("Geekname is: {}".format(self.geekname))
      

if __name__ == "__main__":
  Geek('Neo').printname()
  
```

### PHP
```php

 // File Geek.php

namespace EngineeringTips;

class Geek 
{
  /** @var string */
  private $name;
  
  public function __construct(string $name) 
  {
    $this->name = $name;
  }
  
  public function printname(): void 
  {
    echo $this->name;
  }
}
    
// File main.php
  
include 'Geek.php';

$geek = new Geek('Neo');

$geek->printname();
  
```

# Advanced topics
## Code quality
### Code smells 
    https://en.wikipedia.org/wiki/Code_smell
### SOLID
#### Single Responsibility Principle
  A class should have only a single responsibility, that is, only changes to one part of the software's specification should be able to affect the specification of the class.
    
#### Open/Close Principle
  "Software entities ... should be open for extension, but closed for modification."

#### Liskov Substitution Principle
  "Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program." See also design by contract.

#### Interface Segregation Principle
  "Many client-specific interfaces are better than one general-purpose interface."

#### Dependency Inversion Principle
  One should "depend upon abstractions, [not] concretions."

## Testing
    https://www.amazon.com/gp/product/0321146530/ref=x_gr_w_bb_sout
    https://www.amazon.com/gp/product/0321503627/ref=x_gr_w_bb_sout
## Continuous integration

## Software architecture
### DDD
      https://www.amazon.com/gp/product/0134434420/ref=x_gr_w_bb_sout

# Carreer
  https://insights.stackoverflow.com/survey/2019
  https://roadmap.sh/


# Future reads
## Software development
    https://www.amazon.es/Pragmatic-Programmer-Journeyman-Master-ebook/dp/B003GCTQAE
    https://www.amazon.com/gp/product/0137081073/ref=x_gr_w_bb_sout
    https://www.amazon.com/gp/product/0132350882/ref=x_gr_w_bb_sout
## Project management
    https://www.amazon.com/Mythical-Man-Month-Anniversary-Software-Engineering-ebook/dp/B00B8USS14/ref=pd_sim_351_7
    https://www.amazon.com/Managers-Path-Leaders-Navigating-Growth/dp/1491973897
    https://basecamp.com/books/rework
