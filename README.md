# Password-Generator
F_name = str(raw_input("Enter your first name: "))
L_name = str(raw_input("Enter your last name: "))
S_id = str(raw_input("Enter your student id: "))

S_id_edit = S_id[-3:]
F_name_id = F_name[0:3]
L_name_id = L_name[0:3]

get_login_name = F_name_id + L_name_id + S_id_edit

print "Your assigned login name is: ", get_login_name
