
```
  k 
h   l
  j
```


$$1\frac{10}{30}$$


### vector

``` c++

#include <iostream>
#include <vector>
using namespace std;
// using std::vector;

void display_vector(vector<string> vs) {
    for (int i = 0; i < vs.size(); i++) {
        cout << vs[i] << endl;
    }
}

void display_ivector(vector<int> vs) {
    for (int i = 0; i < vs.size(); i++) {
        cout << vs[i] << endl;
    }
}

int main() {
    vector<int> ivec;             // ivec holds objects of type int
    ivec.push_back(100);
    ivec.push_back(200);

    cout << ivec[0] << endl;
    vector<string> svec; // default initialization; svec has no elements
    vector<string> articles = {"a", "an", "the"};

    cout << articles[0] << endl;
    display_vector(articles);


    vector<int> v1(3); 
    display_ivector(v1);
}
```
