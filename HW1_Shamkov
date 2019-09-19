#!/usr/bin/env python
# coding: utf-8

# In[1]:


def toOurSuspiciousNumber(x):
    if len(list(str(x))) % 2 == 0:
        return list(str(x))
    else:
        return list('0')+list(str(x))
def polyndromQ(x):
    if toOurSuspiciousNumber(x)[:len(toOurSuspiciousNumber(x))//2]==toOurSuspiciousNumber(x)[len(toOurSuspiciousNumber(x))//2:][::-1]:
        return print("True")
    else:
        return print("False")


# In[2]:


def capableOFParking(day,hour):
    if (hour>24 or hour<0) or (day != "Monday" and day != "Sunday" and day != "Wednesday" and day != "Friday" and day != "Tuesday" and day != "Thursday" and day != "Saturday"):
        return print("думаю парковаться не стоит")
    elif (day == "Tuesday" or day == "Thursday" or day == "Saturday") and hour>20:
        return print("left")
    elif  (day == "Tuesday" or day == "Thursday" or day == "Saturday") and hour<19:
        return print("right")
    elif (day == "Monday" or day == "Sunday" or day == "Wednesday" or day == "Friday") and hour<19:
        return print("left")
    elif (day == "Monday" or day == "Sunday" or day == "Wednesday" or day == "Friday") and hour>20:
        return print("right")
    else:
        return print("BOTH")

