#include <iostream>
using namespace std;
int main()
{
    string email,loc,report;
    cout<<"                                  WEATHER APP                       \n";
    /*Name:Janani M
    College name:Vivekanandha College of ENgineering for Women
    datas used:Email id,Location,report
    Methods used:if else statement
    */
    cout << "email id: ";
    cin>>email;
    cout << "current location: ";
    cin>>loc;
    cout << "Do you want the weather for a day or for the week?(Enter'day'or'week'): ";
    cin>>report;
    cout << "The " << report <<" report for "<< loc << " is:\n";
    if (report=="day") 
    {
        int date;
        cout<<"enter date:\n";
        cin>>date;
        cout << "WEATHER: Sunny\n";
        cout<<"TEMPERATURE:\n";
        cout << "High: 75°F\n";
        cout << "Low: 55°F\n";
    } 
    else if (report=="week") 
    {
        cout << "Date:01.05.2023\n";
        cout << "Climate: Sunny\n";
        cout << "High: 75°F\n";
        cout << "Low: 55°F\n";
        cout << "\n";
        cout << "Date:02.05.2023\n";
        cout << "Climate: Cloudy\n";
        cout << "High: 70°F\n";
        cout << "Low: 52°F\n";
        cout << "Date:03.05.2023\n";
        cout << "Climate: rainy\n";
        cout << "High: 62°F\n";
        cout << "Low: 49°F\n";
        cout << "Date:04.05.2023\n";
        cout << "Climate: Cloudy\n";
        cout << "High: 70°F\n";
        cout << "Low: 52°F\n";
        cout << "Date:05.05.2023\n";
        cout << "Climate: thunderstorm\n";
        cout << "High: 70°F\n";
        cout << "Low: 42°F\n";
        cout << "Date:06.05.2023\n";
        cout << "Climate: dry\n";
        cout << "High: 70°F\n";
        cout << "Low: 52°F\n";
        cout << "Date:07.05.2023\n";
        cout << "Climate: sunny\n";
        cout << "High: 70°F\n";
        cout << "Low: 52°F\n";
    }
    else
    {
        cout << "Invalid report type entered\n";
    }

    return 0;
}
