# TimothySpeareGrader
#Calculate average grade
print("Average Grade Calculator")
print("This will help you know you're standing in the class.")
print("Enter your grades from last 5 tests. Hit enter after every score.")
grade1 = input();
if grade1 == 'x':
    exit();
else:
    grade1 = int(grade1);
    grade2 = int(input());
    grade3 = int(input());
    grade4 = int(input());
    grade5 = int(input());
    sum = grade1 + grade2 + grade3 + grade4 + grade5;
    average = sum/5;
    if(average>=91 and average<=100):
    	print("Your Grade is A+");
    elif(average>=81 and average<=90):
    	print("Your Grade is A");
    elif(average>=71 and average<=80):
    	print("Your Grade is B+");
    elif(average>=61 and average<=70):
    	print("Your Grade is B");
    elif(average>=51 and average<=60):
    	print("Your Grade is C+");
    elif(average>=41 and average<=50):
    	print("Your Grade is C");
    elif(average>=0 and average<=40):
    	print("Your Grade is F")
