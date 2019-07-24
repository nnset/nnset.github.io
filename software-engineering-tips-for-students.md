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

$geek = new EngineeringTips\Geek('Neo');

$geek->printname();
  
```

# Learning and improving your skills
## Coding
Use [exercism](https://exercism.io/), you will find lots of exercices for many programming languages.

## Unix/Linux
[Learn Unix](https://es.coursera.org/learn/unix)

## Tools
### Version control systems

Learn [Git](https://try.github.io/)


## Being update
Check some tech conferences : 
* [List of conferences by country](https://techconferences.co/)

Videos:

* [GoTo Conference](https://www.youtube.com/channel/UCs_tLP3AiwYKwdUHpltJPuA)
* [Devoxx](https://www.youtube.com/channel/UCCBVCTuk6uJrN3iFV_3vurg)
* [Web Summit](https://www.youtube.com/channel/UCJtkHqH4Qof97TSx7BzE5IQ/videos)

Follow some people

* [Robert C. Martin](https://twitter.com/unclebobmartin)
* [Martin Fowler](https://twitter.com/martinfowler)

# Carreer
## Tech stack on the real world
Stack overflow makes surveys among their users.
* [2019 survey](https://insights.stackoverflow.com/survey/2019)

## What should I learn?
[Kamran Ahmedse](https://twitter.com/kamranahmedse) and many others colaborators came up with the idea of a "learning roadmap" for software development, check it at [roadmap.sh/](https://roadmap.sh/)

# Advanced topics

## Code smells 
Read about [code smells](https://en.wikipedia.org/wiki/Code_smell)

## SOLID
Read about the [SOLID orinciple](https://en.wikipedia.org/wiki/SOLID).

## Testing
📖[Test Driven Development: By Example](https://www.amazon.com/gp/product/0321146530/ref=x_gr_w_bb_sout)
📖[Growing Object-Oriented Software, Guided by Tests](https://www.amazon.com/gp/product/0321503627/ref=x_gr_w_bb_sout)
    
## Continuous integration

## Software architecture
### DDD
📖[Domain-Driven Design Distilled](https://www.amazon.com/gp/product/0134434420/ref=x_gr_w_bb_sout)

# Future reads
## Software development
📖[The Pragmatic Programmer: From Journeyman to Master (English Edition)](https://www.amazon.es/Pragmatic-Programmer-Journeyman-Master-ebook/dp/B003GCTQAE)
📖[The Clean Coder: A Code of Conduct for Professional Programmers](https://www.amazon.com/gp/product/0137081073/ref=x_gr_w_bb_sout)
📖[Clean Code: A Handbook of Agile Software Craftsmanship](https://www.amazon.com/gp/product/0132350882/ref=x_gr_w_bb_sout)

## Project management
📖[Rework](https://basecamp.com/books/rework)
📖[The Mythical Man-Month, Anniversary Edition: Essays On Software Engineering](https://www.amazon.com/Mythical-Man-Month-Anniversary-Software-Engineering-ebook/dp/B00B8USS14/ref=pd_sim_351_7)
📖[The Manager's Path: A Guide for Tech Leaders Navigating Growth and Change](https://www.amazon.com/Managers-Path-Leaders-Navigating-Growth/dp/1491973897)
