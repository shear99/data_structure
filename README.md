<br/>

<img src= "https://img.shields.io/badge/Java-v11.0.5-blue&?logo=Java&color=blue"/> <a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fkdgyun%2FData_Structure&count_bg=%233DC8C1&title_bg=%23285C8C&icon=&icon_color=%23E7E7E7&title=Visits&edge_flat=false" align="right"></a>


<br/>

# Data Structure

<br/><br/> 

&nbsp;&nbsp;&nbsp; 자료구조 구현 소스 코드들이 있는 곳입니다.  

<br/><br/>  


Project
-----------
<br/>

#### DataStructure  




> - 자료구조 구현에 필요한 폴더들이 있습니다.
> - Java11를 기준으로 구현됩니다.
> - Java11 API : [Java API](https://docs.oracle.com/en/java/javase/11/docs/api/index.html)

</br></br>
#### [Preview subFolder]
> - Interface       : 자료구조를 구현하는데 필요한 기본 인터페이스가 있습니다.
> - \_01\_ArrayList : ArrayList를 구현한 소스코드가 있습니다.
> - \_02\_SinglyLinkedList : SinglyLinkedList를 구현한 소스코드가 있습니다.
> - \_03\_DoublyLinkedList : DoublyLinkedList를 구현한 소스코드가 있습니다.
> - \_04\_Stack : Stack을 구현한 소스코드가 있습니다.
> - \_05\_ArrayQueue : 배열로 Queue를 구현한 소스코드가 있습니다.
> - \_06\_LinkedListQueue : 연결리스트로 Queue를 구현한 소스코드가 있습니다.
> - \_07\_ArrayDeque : 배열로 Deque를 구현한 소스코드가 있습니다.
> - \_08\_LinkedListDeque : 연결리스트로 Deque를 구현한 소스코드가 있습니다.
> - \_09\_Heap : 배열로 힙을 구현한 소스코드가 있습니다.
> - \_10\_PriorityQueue : 우선순위 큐를 구현한 소스코드가 있습니다. (배열 힙 기반)
> - \_11\_HashSet : Separate Chaining 방식을 적용한 HashSet을 구현한 소스코드가 있습니다.
> - \_12\_LinkedHashSet : Separate Chaining + LinkedList 방식을 적용한 LinkedHashSet을 구현한 소스코드가 있습니다.


<br/><br/>

-----------------


#### How to Use (download ZIP) on Eclipse
<br/>

- **1. Project import** <br /> <br /> Window -> File -> New -> Java Project -> uncheck the **"Use default location"** and browse the **DataStructure** folder
-> Finish

<br /><br />

- **2. Build path** <br /> <br /> Your Project -> Build Path -> Configure Build Path -> Project -> select the class path -> add -> Select **DataStructure** -> Apply and Close

<br /><br />

- **3. import class**

```
import [data structure package name].[data structure name];
```

</br></br></br>

**Most data structure classes have sorting methods.**

</br>

Data structure to support sort method:
- **ArrayList**
- **SinglyLInkedList**
- **DoublyLInkedList**
- **Stack**
- **ArrayQueue**
- **LinkedListQueue**
- **ArrayDeque**
- **LinkedListDeque**

</br></br>

```java
//ex.

import _01_ArrayList.ArrayList;

class YourClass {
	public static void main {
		ArrayList<Integer> list = new ArrayList<Integer>();
		/*
		 your code
		*/
		
		list.sort();
	}
}
```



<br/><br/>

 
<br/><br/>

&nbsp;&nbsp;&nbsp; 블로그에서 포스팅과 동시에 지속적으로 업데이트 예정

<br/><br/>
<br/><br/>

-----------------

#### 구현 대한 내용은 블로그에 기재하고 있습니다.  
<br/>

- [Stranger's LAB](https://st-lab.tistory.com/category/자료구조/Java)
<br/>
&nbsp;&nbsp;&nbsp; 부분적으로 추가 구현 또는 차이가 있을 수 있습니다.

<br/><br/>


