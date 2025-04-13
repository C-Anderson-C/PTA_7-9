# PTA_7-9
# 用天平找小球
# 三个球A、B、C，大小形状相同且其中有一个球与其他球重量不同。要求找出这个不一样的球。

# 输入格式：输入在一行中给出3个正整数，顺序对应球A、B、C的重量。

# 输出格式：在一行中输出唯一的那个不一样的球。
```cpp
#include <iostream>
using namespace std;
int main() {  //幼稚园小朋友都会的题目
	int a, b, c;
	cin >> a >> b >> c;
	if (a == b) {  //注意是==不是=
		cout << "C";  //是大写的，题目总是喜欢这样搞人家
	}
	else if (b == c) {
		cout << "A";
	}
	else if (a == c) {
		cout << "B";
	}
	return 0;

}
