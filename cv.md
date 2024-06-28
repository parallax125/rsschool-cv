

![alt-photo](/photo.jpeg)

# **Kovylin Evgeniy**

*Contact: telegram @Evgeniy_A_K | krasnodarkea@gmail.com*


## **About me:**

I have been working as a QA engineer for 5 years. I have experience in manual testing of both front and back ends. There is a desire to master the profession of a webmaster. I am also interested in programming microcontrollers based on Arduino.


## **Skills** 

### ***Tech skills:*** 
Some C, C++ (on Arduino), Python, JavaScript, HTTP, HTML, CSS, Kafka, MQ Rabbit, bash;<br>

### ***Databases:*** 
Oracle, MS SQL Server;<br>

### ***Environment & Tools:*** 
Windows, Debian, Mac OS, Visual Studio, PyCharm CE, Jira, Confluence, Swager, Postman, Arduino IDE, Google Script.<br>


## **Code example** 

```C++ (arduino)
void arrowUP (int resultInt, int sum)
{
  int iterations = 8; 
  
  for (int i = 0; i < iterations; i++) 
  {
    if (i % 2 == 0) 
    { 
      String symb = "+";

      currentValue += 5;

      displayReload(resultInt, sum, symb);

      Strelka(currentValue);

    } else 
    { 
      currentValue -= 5;

      String symb = "+";

      displayReload(resultInt, sum, symb);

      Strelka(currentValue);

    }

    delay(150);
  }

}
```

``` JavaScript (ES5) (Google script)
function findFirstEmptyCell2() {
  var sheet = SpreadsheetApp.getActiveSpreadsheet().getSheetByName('Ошибки');
  var columnValues = sheet.getRange("E:E").getValues();
  var lastRow = sheet.getLastRow();
  var today = new Date().getDay();
  if (today === 0 || today === 6) {
    return;
  }
  
  for (var i = lastRow; i >= 1; i--) {
    if (columnValues[i-1][0] === "") {
      var currentValue = sheet.getRange(i+1, 4).getValue();
      sheet.getRange("D" + i).setValue(currentValue);
      var currentValue_E = sheet.getRange(i, 5);
      let date = new Date();
      currentValue_E.setValue(date);
      break;
    }
  }
  sheet.insertRows(4, 1);
  return sheet.getRange(lastRow + 1, 5);
}
```
## **Experience** ##

### **QA middle manual testers | 2023 - Present**<br>
***bank Renessans Credit***

#### Participated in the SME project. Launch of a new direction in the bank for servicing small and medium-sized business clients. #

* working with technical documentation, assessing tasks, reviewing requirements;
* writing test scripts, drawing up test plans; creating a bug report, creating issues (Jira, Confluence);
* functional, system and integration testing of web applications (front, business logic); Golden Crown(SBP); RBS web applications (web, iOS, Android); CRM; ABS CFT, Way4, Profile, Diasoft; microservice chains;
* testing integration between web application and DBMS (Postman, DBeaver, Oracle SQL Developer, PuTTY, Swagger);
* working with logs - analysis, localization of defects; (Kibana, OpenShift, Comunda);
* regression testing;
* interaction with developers, business, BA and SA.

## **QA middle manual testers | 2021-2023** ##<br>
***ООО “АйТиКью Груп”***

* Integration testing between the site mkb.ru and CRM Siebel;
* Functional testing of the Credit Conveyor web application (front, business logic);
* Testing integration between web application and DBMS (Postman, Rabbit, Oracle SQL Developer);
* Regression testing;
* Writing test scripts, drawing up test plans (TestRail); Opening a bug report, creating issues (Jira);
* reviewing business logic requirements (Confluence);
* Support of PSI (showing functionality to users);
* Testing a mobile application on Android and iOS operating systems;
* Testing integration between services regarding sending and receiving payments.

## **QA manual testers | 2018-2021** ##<br>
***EntMedia***

## testing Internet portals and business logic of web applications ##
* Analysis of technical documentation;
* Drawing up a test plan, test cases;
* testing time estimate;
* carrying out functional, integration and regression testing;
* Interaction with a team of developers and analysts.

## *Languages* ##

* English - A2 elementary;
* Russian - Native.