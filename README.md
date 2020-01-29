# IBM Cloud Garage Method

# javascript test-driven-development [TDD]
This repository is used for the [IBM Garage Method TDD course](https://www.ibm.com/cloud/garage/content/course/test-driven-development/) to illistrate the fundamentals of TDD using javascript

___


## Getting Started

#### Prerequisites
You will need the following installed 
* Node.js
* Git command line

#### Clone the repo, install and run the tests:
To setup and execute the tests perform the following in a terminal window
````
git clone git@github.com:ibm-cloud-academy/javascript-tdd.git
cd javascript-tdd
npm install mocha --save-dev
npm install should --save-dev
npm test
````

___
## References

### [The Four Rules of Simple Design](https://martinfowler.com/bliki/BeckDesignRules.html):

* **_Passes the tests_**
* **_Reveals intention_**
* **_No duplication_**
* **_Fewest elements_**


### [The Transformation Priority Premise](https://8thlight.com/blog/uncle-bob/2013/05/27/TheTransformationPriorityPremise.html):

````
(01) [{} –> nil] no code => return nil

(02) [nil->constant] nil => simple constant

(03) [constant->constant+] simple constant => complex constant

(04) [constant->scalar] complex constant => variable or an argument

(05) [statement->statements] adding more unconditional statements.

(06) [unconditional->if] splitting the execution path

(07) [scalar->array]

(08) [array->container]

(09) [statement->recursion]

(10) [if->while]

(11) [expression->function] replacing an expression with a function or algorithm

(12) [variable->assignment] replacing the value of a variable.
````


### [Simplified Transformation Priority Premise](https://8thlight.com/blog/micah-martin/2012/11/17/transformation-priority-premise-applied.html):

````
(01) constant => a value

(02) scalar => a local binding, or variable

(03) invocation => calling a function/method

(04) conditional => if/switch/case/cond

(05) while loop => applies to for loops as well

(06) assignment => replacing the value of a variable
````

___
