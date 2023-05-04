<h1 id="code-sample">Code Sample</h1>
<h1 id="this-code-sample-was-written-by-me">This code sample was written by me</h1>
services={'Air freshener':1,'Rain repellent':2,'Tire shine':2,'Wax':3,'Vacuum':5}
base_wash=10
total=0
# read service choices
print("What is your desired service?")
service_choice1=input()
service_choice2=input()
# add 10 into total
total = total +10
print("ZyCar Wash")
print("Base car wash: $10")
# if service_choice1 is not '-',then
if service_choice1!='-':
    # add its cost into total
    total=total+services[service_choice1]
    # display service choice and cost
    print(service_choice1,"- $"+str(services[service_choice1]))

# if service_choice2 is not '-',then
if service_choice2!='-':
    # add its cost into total
    total=total+services[service_choice2]
    # display service choice and cost
    print(service_choice2,"- $"+str(services[service_choice2]))
print("----")
# display total
print("Total price: $"+str(total))<p><a href="./README.md">Return to home</a></p>
  <p><a href="./Skills.md">Go to Skills page</a></p>
  <p><a href="./Work.md">Go to Work page</a></p>
  <p><a href="./Hobby.md">Go to Hobbies page</a></p>
