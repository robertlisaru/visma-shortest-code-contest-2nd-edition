<img align=center width=200px src="https://upload.wikimedia.org/wikipedia/commons/7/77/Visma_logo.png"/>
<img align=center width=200px src="https://www.ulbsibiu.ro/wp-content/uploads/prezentare/LOGO-ULBS_orizontal.png"/>


## visma-shortest-code-contest-2st-edition (December 2016)
Solve the C++ challenge using the shortest amount of code (what is known as [codegolf](https://en.wikipedia.org/wiki/Code_golf)).

### The challenge
Write a C++ program that generates this text file: [arecibo.txt](https://github.com/robertlisaru/visma-shortest-code-contest-2nd-edition/blob/main/arecibo.txt)

### My 394 characters [solution](https://github.com/robertlisaru/visma-shortest-code-contest-2nd-edition/blob/main/source.cpp)
same 3rd place 🥉 as in 1st edition
```cpp
﻿#include<fstream>
std::ofstream f("arecibo.txt");int i,j;int main(){for(auto s=U"RШʪЬࢰӚ૒Ռ(((ب+Ȩ+Ȩ-Ȩ/ب((ౠـࠨƸീق࿦ࠇ((Ĩ*((¨)ྨG((ౘ݀࠰8ഴς࿦ࠇ((ī*+(«)ྫG+(ȩ,ī0ë8Y+ƨYë8Ī0ȫ,Ы,Щ0Ȫ8ĨèƨɢبȪ(ȷШȿʃOŧய_-cȭgȭXȵШ((Ϊ(ϐսΨż(Ũ7ШgܨĈǨƨͨØڈǀѸʰѰҰm¨j¨h¨:Ш߇ʠ";s[i];++i%2||f<<"\n")for(j=11-i%2;~j;f<<(s[i]-40>>j--&1));}
```

<br><hr><br>

![15137676_665995730242754_7454082262766412519_o](https://github.com/robertlisaru/visma-shortest-code-contest-2nd-edition/assets/40792547/466c0ce1-1340-407e-a0d3-0d6733496cc5)
