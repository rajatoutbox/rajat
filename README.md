# list as user input using dictionary

# create empty list
student_data = []

# input from user for the number of entries as n
n = int(input("Enter the number of entries: "))

# iterating until the number of entries
for i in range(n):
    roll_no = int(input("Roll no.: "))
    name = input("Name: ")
    address = input("Address: ")
    mail_id = input("Mail ID: ")
    contact = input("Contact: ")

    # create a dictionary for each student and append it to the list
    student_entry = {
        "Roll No": roll_no,
        "Name": name,
        "Address": address,
        "Mail ID": mail_id,
        "Contact": contact
    }
    student_data.append(student_entry)

# print student_data
print(student_data)

