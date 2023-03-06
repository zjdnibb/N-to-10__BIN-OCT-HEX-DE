#include<bits/stdc++.h>
使用命名空间标准;
int s[100];
int main（void){
	整数 i=0，c=1;
	长长A;

	双R;
辛>>>>;
	如果 （a>=r）{
		而（a>=r）{
			if（a*1.0/r*1.0==int（a/r））{
s[i]=0;
				//s[i+1]+=1;

			}还 {
s[i]+=a%int（r）;
				//if（s[i]>=r）{
				//	s[i]=s[i]-r;
				//}
			}
i++;
a=int（a/r）;
		}
s[i]=a;
	}还 {
i=1;
s[0]=a;
	}
	for（int j=i;j>-1;j--）{
		if（s[j]==10){
cout<<“A”;
		}否则如果（s[j]==11){
cout<<“B”;
		}否则如果（s[j]==12){
cout<<“C”;
		}否则如果（s[j]==13){
cout<<“D”;
		}否则如果（s[j]==14){
cout<<“E”;
		}否则如果（s[j]==15){
cout<<“F”;
		}else cout<<s[j];
	}


	
}
