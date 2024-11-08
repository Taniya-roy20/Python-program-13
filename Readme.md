# Program 13: WAP to accept a name from a user. Raise and handle appropriate exceptions if the text entered by the user contains digits and/or special characters.
code=name=input("enter a name ")
<br>
try:
<br>
    if name.isalpha():
    <br>
        print("This is correct name")
        <br>
    else:
    <br>
        raise Exception (" There is NameErrror")
      <br>      
except Exception as e:
<br>
    print(e)
  ![image](https://github.com/user-attachments/assets/bb6552f3-e8c1-4244-8e1c-1f917ef92520)
  ![image](https://github.com/user-attachments/assets/a7492e39-a14b-4ae9-a980-587deff01832)


