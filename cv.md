---------------------------------------------------------------------------------------------------------------
# ***Aleksei Sv***
---------------------------------------------------------------------------------------------------------------
## **Junior**

### *Contact information*

**1. Phone +375 29 123 45 67**

**2. E-mail: alex@mail.ru**

# Preffered method for contact - e-mail

### *Me and my expirience*

 |  ***Year*** |      ***Expirience***          |
  |:------------|:-------------------------------|
  |   **2022**  |Graduate the java course        |
  |   **2023**  |Graduate the javascript course, I hope|

### *Skills*

## 1. I can do:
   ### - this;
   ### - that;
## 2. I also can do:
   ### - and this;
   ### - and that

### *Code examples*

package ***.*****************.task_7.controller;

import ***.*****************.task_7.bean.RegExBean;
import ***.*****************.task_7.service.RegExService;
import ***.*****************.task_7.view.RegExView;
import org.apache.logging.log4j.LogManager;
import org.apache.logging.log4j.Logger;

import java.io.IOException;

public class RegExController extends RegExService{

    public static Logger logger = LogManager.getLogger(RegExController.class);

//    public static RegExController regExController;
    public static RegExBean regExBean;
    public static RegExService regExService;
    public static RegExView regExView;

    public  void main() {

//        regExController = new RegExController ();
        regExBean = new RegExBean ();
        regExService = new RegExService ();
        regExView = new RegExView ();

        regExBean.setChoiceByTheUser(regExView.chooseByTheUser());
        try {
            regExService.workWithRegEx(regExBean.getChoiceByTheUser());
        } catch (IOException e) {
            e.printStackTrace();
        }

        regExView.catchTheResult(regExService.answerForTheController());

    }
}


### *Courses*

#### 1. Java web development
#### 2. Fundamentals of cloud technologies and web 2.0 services

### *Languages*
- native - belorussian
- can speak - russian, english. The last one - I have reached the A2+ level by now

--------------------------------------------------------------------------------------------------

# ***Hope your are satisfied!!!!!!!!!!!!!***
# 😉
