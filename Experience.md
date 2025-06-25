<!DOCTYPE html>
<html>
    <head>
<h1 id="code-sample">Code Sample</h1>
<h2 id="this-code-sample-was-written-by-me">This code sample was written by me. It outputs the total price of all the selected items.</h2>
    </head>
    <body>
        
services={'Air freshener':1,'Rain repellent':2,'Tire shine':2,'Wax':3,'Vacuum':5}

base_wash=10

total=0

print("What is your desired service?")

service_choice1=input()

service_choice2=input()

total = total +10

print("ZyCar Wash")

print("Base car wash: $10")

if service_choice1!='-':
    
total=total+services[service_choice1]
    
print(service_choice1,"- $"+str(services[service_choice1]))

if service_choice2!='-':
    
total=total+services[service_choice2]
    
print(service_choice2,"- $"+str(services[service_choice2]))

print("----")

print("Total price: $"+str(total))
      </body>     
  <p><a href="./AboutMax.md">About Me</a></p>
  <p><a href="./Skills.md">Skills</a></p>
  
    </html>
