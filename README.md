# my_project
// app 1 even : odd 

//     int a ;
//     cout<< "enter a : ";
//     cin>>a;
//     int x ;
//     cout<< "\nenter x : ";
//     cin>>x;

//     if( a > 0)
//     {
//         cout<<"this num a postive .";
        
//     }if (a < 0)
//         {
//             cout<<"this num a nagtive .";
//         }else 
//         {
//             cout<<"zerooooo ";
//         }

//     app2 => biger num 

//     int a,b,c;
//     cout<<"a:";
//     cin>>a;
//     cout<<"\nb:";
//     cin>>b;
//     cout<<"\nc:";
//     cin>>c;


//     if (a>b && a>c )
//     {
//         cout<<"this a biger num : "<<a;
//     }else if (b>a&& b>c)
//     {
//         cout<<"this a biger num : "<<b;
//     }else
//     cout<<"this a biger num : " <<c;


//     app3 => uder point chick  

//     int point ;
//     cout<<"enter point : ";
//     cin>>point ;

//     if (point >= 0 && point <= 500 )
//     {
//         cout << "not bad .";
//     }else if (point >= 501 && point <= 1000 )
//     {
//         cout<<"good .";
//     }else if (point >= 1001 && point <= 1500)
//     {
//         cout <<"very good .";
//     }else if (point < 0)
//     {
//         cout <<"error xx-xx";
//     }else 
//     {
//         cout<<"genis .";
//     }

//     double x, y;
// cin >> x;
// cin >> y;
// double quotient = x / y;
// cout << quotient << endl;

// double income, tax; 
// int age; 
// cin >> income; 
// cin >> age; 
// if (age < 60) 
// { 
// tax = income * 0.25;
// }
// else 
// { 
// tax = income * 0.2; 
// }
// cout << "The tax amount is: " << tax; 

// double A, B, C; 
// cin >> A >> B >> C; 
// double Sum = A + B + C; 
// double Average = (Sum) / 3;
//  cout << Average << endl;

//     double A, B, C; 
// cin >> A >> B >> C;
//  double Sum = A + B + C;
//  double Average = (Sum) / 3; 
// cout << Average << endl; 

// double purchase, discount; 
// cin >> purchase; 
// if (purchase <= 1000) 
// { 
// cout << "There is no discount!" << endl;
//  }
//  else 
// { 
// discount = purchase * 0.1;
//  purchase = purchase - discount;
//  cout<<"The purchase is "<< purchase;
// }

// int num ;
// cout<<"enter num 1:10 : ";

// cin>>num;

// switch (num)
// {
// case 1 : 
// cout<<"12345...";
    
// case 2 :
// cout<<"2345...";
//     break;
// case 3 :
// cout<<"3456... ";
//     break;
// case 4 : 
// cout<<"45678...";
//     break;

// default:
// cout<<"error";

// }

===================================================================
===================================================================


// //app => discount appliction

//     int price = 1000 ;
//     int discount = 0;
//     int years ;
//     cout << " plz enter a years in a jop : ";
//     cin>>years;

//     switch (years)
//     {
//         case 10 :
//             discount = 50;
//             break ;
//         case 11:
//             discount = 50;
//             break;
//         case 12:
//             discount = 50;
//             break;
//         case 13:
//             discount = 50;
//             break;
//         case 14:
//             discount = 50;
//             break;
//         case 15:
//             discount = 150;
//             break;
//         case 16:
//             discount = 150;
//             break;
//         case 17:
//             discount = 150;
//             break;
//         case 18:
//             discount = 150;
//             break;
//         case 19:
//             discount = 150;
//             break;
//         case 20:
//             discount = 300;
//             break;
//     }

//     cout << "\nthe price is : "<<price - discount ;


=============================================================
===============================================================



               // simple calculator


    // cout << "\n[1] + ";
    // cout << "\n[2] - ";
    // cout << "\n[3] / ";
    // cout << "\n[4] * ";
    // cout << "\nplz enter the oprator : ";
    // cin >> oprator;





    // if (oprator == 1)
    // {
    //     cout << num1 + num2;
    // }else if (oprator == 2)
    // {
    //     cout << num1 - num2;
    // }else if (oprator == 3)
    // {
    //     cout << num1 / num2;
    // }else if (oprator == 4)
    // {
    //     cout << num1 * num2;
    // }else 
    // {
    //     cout << "error ";
    // }
    // int num1, num2, oprator;
    // cout << "plz enter the num 1 : ";
    // cin >> num1;
    // cout << "\nplz enter the num 2 : ";
    // cin >> num2;


============================================================================
============================================================================


    // switch(oprator)
    // {
    //         case 1:
    //     cout<<num1 <<" + "<<num2<<" = "<<num1 + num2 ;
    //     break;
    //     case 2:
    //         cout << num1 << " - " << num2 << " = " << num1 - num2;
    //         break;
    //     case 3:
    //         cout << num1 << " / " << num2 << " = " << num1 / num2;
    //         break;
    //     case 4:
    //         cout << num1 << " * " << num2 << " = " << num1 * num2;
    //         break;
    //         default:
    //         cout<< "the operat is not valid\n";
    // }


============================================================================
=============================================================================





#include <iostream>
using namespace std;
int main()
{

    /*Complete the sequence12*/

    int point = 0 ;
    int answer[3];

    cout<<"plz enter answer : "<<endl;
    cout<<" < 2 | 4 | 6 | 8 | 10 | ?? >"<<endl;
    cout<<"your answer is : ";
    cin>>answer[0];

    cout << "plz enter answer : " << endl;
    cout << " < 1 | 3 | 5 | 7 | 9 | ?? >" << endl;
    cout << "your answer is : ";
    cin >> answer[1];

    cout << "plz enter answer : " << endl;
    cout << " < 2 | 4 | 8 | 16 | 32 | ?? >" << endl;
    cout << "your answer is : ";
    cin >> answer[2];

    int play[3][6] = 
    {
        {2,4,6,8,10,12},
        {1,3,5,7,9,11},
        {2,4,8,16,32,64}
    };

    if(answer[0] == play[0][5])
    {
        point++;
    }
    if (answer[1] == play[1][5])
    {
        point++;
    }
    if (answer[2] == play[2][5])
    {
        point++;
    }

    cout<< "your point "<<point<<" from 3."<< endl;

    return 0;
}

=========================================
=========================================

#include <iostream>
using namespace std;
int main()
{

    string products[] = {" item 1 ", " item 2 ", " item 3 " };
    string sizes[] = {" small " , " large " , " x-large "};

    for(int i = 0 ; i < 3 ; i++)
    {
        cout<<"product name : ";
        cout<<products[i]<<endl;
        cout<<"size : "<<endl;
        for(int n = 0 ; n < 3 ; n++)
    {
        cout<<sizes[n];
        if( n < 2)
        {
            cout<<",";
        }
    }
        cout<<"\n";
        cout<<"=======================\n";
    }

    return 0;
}


==========================================================



//count positive and even namber only



    int start = 0;
    int nums[] ={10,30,-55,40,-40,29,71,83};  
    int numsize = sizeof(nums)/sizeof(nums[0]);
    for(int i = 0 ;i < numsize ; i++)
    {
        if(nums[i] > 0 && nums[i] %2 == 0)
        {
        start += nums[i];
        }
    }cout<<start<<endl;

=======================================================================



    int arry[5];
    int inp;
    cout<<"plz enter the 5 nums :\n ";
//[0,1,2,3,4]
    for(int i = 4 ; i < 5 ; i-- )
    {
        cin>>inp;
        arry[i] = inp;
        if(arry[0] == 1 )
        {
            break;
        }
    }

    cout<<"\n=====================\n";

    for (int i = 0; i < 5; i++)
    {
        cout<<arry[i]<<endl;
    }





====================================================


function





int trb(int x ,int y )
{
    int r ;
    r = x*y ;
    return r;
}
int gm3(int x, int y)
{
    int r ;
    r= x+y;
    return r;
}
int ksma(int x, int y)
{
    int r;
    r = x / y;
    return r;
}
int tr7(int x, int y)
{
    int r;
    r = x - y;
    return r;
}
int swap(int x , int y)
{
    int t ;
    t = x;
    y= x ;
    t = y;

    return t;
}
int fact(int N )
{
    int f = 1;
    for(int i = 1; i <= N ; i++ ){
    f = f*i;
}

    return f;

}



======================================================================



#include <iostream>
using namespace std;
void clac(int num1 , int num2 , string op)
{
    cout<<num1<<op<<num2<<"=";
    if (op == "+")
    {
        cout<<num1+num2;
    }
    else if (op == "-")
    {
        cout << num1 - num2;
    }
    if (op == "/")
    {
        cout << num1 / num2;
    }
    if (op == "*")
    {
        cout << num1 * num2;
    }
}
int main()
{
    clac(10,90,"*");
    return 0;
}


=====================================================================


#include <iostream>
using namespace std;
int main()
{
	int a, b;
	string op;
	cout << "plz enter the num1 : ";
	cin >> a;
	cout << endl;

	cout << "plz enter the oprator : ";
	cin >> op;
	cout << endl;
	
	cout << "plz enter the num2 : ";
	cin >> b;
	cout << endl;

if (op == "+")
	{
	cout << a << " + " << b << " = " << a + b;
	}
	else if (op == "-")
	{
		cout <<a <<" - "<<b<<" = " << a - b;
	}
	else if (op == "*")
	{
	cout << a << " * " << b << " = " << a * b;
	}
	else if (op == "/")
	{
	cout << a << " / " << b << " = " << a / b;
	}
	else
	{
		cout << "error";
	}


	return 0;
}





===========================================================



        //swap case app

    string nameone = "YOUSef";
    int namesize =size(nameone);

    for(int i = 0 ; i < namesize ; i++ )
    {
        if(isupper(nameone[i]))
        {
            cout<<char(tolower(nameone[i]));
        }else 
        {
            cout<<char(toupper(nameone[i]));
        }
    }

    cout<<"\n==============================\n";


        //Remove spaces app

    string name = "y  ou \n\t  sef";
    int namesizee = size(name);

    for(int i = 0 ; i < namesizee ; i++)
    {
        if(isspace(name[i]))
        {
            continue;
        }
        cout<<name[i];
    }




=============================================================

int num[20] = {1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20};
    int sum = 0 ;
    int sun = 0 ;
    int i = 0;
    for( ; i < 21 ; i++ )
    if ( i % 2 == 1)
    {
        sum = sum + num[i] ;
        cout<<num[i];
        cout << "The sum of even numbers : " << sum << endl;
    }
    i = 0;
    if (i % 2 == 0 ) {
        sun = sun * num[i];
        cout << "The  : "<< sun <<endl;
    }


==================================================




#include <iostream>
using namespace std;
int main()
{
	char z;
	cout << "plz enter : ";
	cin >> z;
	cout << endl;
	if (z == 'p' || z == 'P')
	{
		cout << "pink";
	}
	else if (z == 'g' || z == 'G')
	{
		cout << "Gray";
	}
	else if (z == 'b' || z == 'B')
	{
		cout << "brown";
	}
	else
	{
		cout << "error";
	}
}




====================================================================



#include <iostream>
using namespace std;
int main()
{
	string str;
	cin >> str;
	string R;

	for (int i = str.length(); i >= 0; i--)
	{
		R += str[i];
	}
	cout << R;
	return 0;
}



===========================================================================

#include <iostream> 
using namespace std;

int main()
{
    // Clock shows h hours, m minutes and s seconds after midnight.
    int h, m, s;
    cin>>h,m,s;

    if (h >= 0 && h <= 23 && m >= 0 && m <= 60 && s >= 0 && s <= 60)
    {
        h *= 3600000;
        m *= 60000;
        s *= 1000;
    }
    else
        cout << "You wrong to put number" << endl;
    cout<<h + m + s;
    return 0;
    // your code here
}



