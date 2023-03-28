#include<iostream>
#include<iomanip>
using namespace std;
int main(void)
{
	cout<<"2022114561 黎渊"<<endl;
	double w,h,bmi;
	cout<<"请输入体重（公斤）：";
	cin>>w;
	cout<<"请输入身高（厘米）：";
	cin>>h;
	bmi=w/(h*h*0.0001);
	cout<<"BMI="<<fixed<<setprecision(2)<<bmi;
	if(bmi<18.5)
		cout<<"，偏瘦！"<<endl;
	else if(bmi<24)
		cout<<"，正常！"<<endl;
		else if(bmi<27)
			cout<<"，偏胖！"<<endl;
			else if(bmi<30)
		        cout<<"，肥胖！"<<endl;
				else if(bmi<40)
					cout<<"，重度肥胖！"<<endl;
					else
						cout<<"，极重度肥胖！"<<endl;
	

    return 0;
}
