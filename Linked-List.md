# Chapter 1: Linked Lists
## 1. Singly Linked List

<p> Linked List and List Node Definition </p>

<code>
  // List.h
  #include <string>
  using namespace std;
  
  class ListNode 
  {
    public:
      ListNode(int);
      ListNode(int, ListNode *);
      ListNode *get_Next() { return next; }
    
    private:
      int data;
      ListNode *next;
  }
  
  class List
  {
    public:
      List(String);
      List();
    private:
      ListNode *first;
      String name;
  }
</code>
  
<p> Methods for Linked Lists </p>
  1. Count
  2. Print
  3. Search
  4. Insert Node
  5. Delete Node
  
<code> 
  int List::Count()
  {
    int result = 0;
    ListNode *p = first;
    while (p != null)
    {
      result++;
      p = p->getNext();
    }
  }
</code>
  
<code> 
</code>
