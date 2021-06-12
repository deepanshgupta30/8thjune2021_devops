# 11thjune2021_devops
import time
import os
user_input='''
press 1 for current time and date
press 2 for ordering food
press 3 for speak to the manager
press 4 for laundary service
press 5 for room service
press 6 for running another code
press 7 to drop the call
'''
print (user_input)
#taking user choice
user_choice= input()
print("user choice is:", user_choice)
if user_choice=='1':
    print ("current time is:", time.ctime())

elif user_choice=='2':
    print("connecting to restraunt")

elif user_choice=='3':
    print("connecting to the reception")

elif user_choice=='6':
    print(os.system('python deepansh.py'))

else :
    print("bhag jaa hotel se") 
