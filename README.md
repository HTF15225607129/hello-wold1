#ifndef  MSERIAL_H_
#define  MSERIAL_H_
#include <Arduino.h>
class MSerial
{
  public:
   void SerialDataCheck(String inputString);
   void getnum(String inputString);
  private:
   String num="";
};//注意这里的分号不要漏掉

#endif
