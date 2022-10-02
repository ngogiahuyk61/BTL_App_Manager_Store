#include <iostream>

using namespace std;
class person
{
    int age;
    char name[30];
    char employeeID[20];
	int day,month,year;
    public:
    void get_details(void)
    {
    cout<< "Enter your Name:"<<endl;
    cin>>name;
    cout<< "Enter your Age:"<<endl;
    cin>>age;
	cout<< "Enter your ID:"<<endl;
    cin>>employeeID;
	cout<< "Enter your Date:"<<endl;
    cin>>day>>month>>year;
    }
    void display_details(void);


};

void person::display_details(void)
{
    cout<< "NAME:"<<name<<endl;
    cout<< "AGE:"<<age<<endl;
    cout<< "ID:"<<employeeID<<endl;
    cout<< "DATE:"<<day<<"/"<<month<<"/"<<year<<endl;
}

int main()
{
    person p;
    p.get_details();
    p.display_details();
    return 0;
}
