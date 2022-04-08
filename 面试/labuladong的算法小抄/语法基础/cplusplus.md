# C++ 语法基础
## 堆栈stack
### 初始化方法
stack<int> stk;
stack<string> stk;
### 返回堆栈是否为空
bool empty();
### 返回堆栈中元素的个数
size_type size();
### 在堆栈中添加元素
void push(const value_type& val);
### 返回栈顶元素的引用
value_type& top();
### 删除栈顶的元素
void pop();
## 队列queue
###
