- 👋 Hi, I’m @Iill0
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Iill0/Iill0 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
m
import os
print("1.شبه ثلاثي بـ(-)")
print("2.شبه ثلاثي(.)")
print("3.شبه ثلاثي عشوائي")
print("4.مخصص")
sa = input("اختار:")
os.system("COLOR A")
if sa == "1":

    print("مكانها؟")
    print("1| (_***)")
    print("2| (*_**)")
    print("3| (**_*)")
    print("4| (***_)")
    da = input("اختار:")
    if da == "1":
        uesr = '_'  # اليوزر المراد التخمين عليه بين النقطتين اكتبه
        chars2 = 'qwertyuiopasdfghjklzxcvbnm0123456789'  # ارقام واحرف لو ترغب
        amount = input('كم عدد اليوزرات ؟')
        amount = int(amount)

        length2 = 3
        length2 = int(length2)

        for password in range(amount):
            password = ''

            for item in range(length2):
                password = ''
            for item in range(length2):
                password += random.choice(chars2)
            bb= uesr + password
            print(bb)
            with open('user.txt', 'a') as x:
                x.write(bb + '\n')
    if da == "2":
        uesr = '_'  # اليوزر المراد التخمين عليه بين النقطتين اكتبه
        chars2 = 'qwertyuiopasdfghjklzxcvbnm0123456789'  # ارقام واحرف لو ترغب
        amount = input('كم عدد اليوزرات ؟')
        amount = int(amount)

        length2 = 3
        length2 = int(length2)

        for password in range(amount):
            password = ''

            for item in range(length2):
                password = ''
            for item in range(length2):
                password = random.choice(chars2)
            for item in range(2):
                password1 = ''
            for item in range (2):
                password1 += random.choice(chars2)
            ba = password + uesr + password1


            print(ba)
            with open('user.txt', 'a') as x:
                x.write(ba +'\n')

    if da == "3":
        uesr = '_'  # اليوزر المراد التخمين عليه بين النقطتين اكتبه
        chars2 = 'qwertyuiopasdfghjklzxcvbnm0123456789'  # ارقام واحرف لو ترغب
        amount = input('كم عدد اليوزرات ؟')
        amount = int(amount)

        length2 = 3
        length2 = int(length2)

        for password in range(amount):
            password = ''

            for item in range(2):
                password = ''
            for item in range(2):
                password += random.choice(chars2)
            for item in range(1):
                password1 = ''
            for item in range(1):
                password1 += random.choice(chars2)
            bd = password + uesr + password1

            print(bd)
            with open('user.txt', 'a') as x:
                x.write(bd + '\n')
    if da == "4":
        uesr = '_'  # اليوزر المراد التخمين عليه بين النقطتين اكتبه
        chars2 = 'qwertyuiopasdfghjklzxcvbnm0123456789'  # ارقام واحرف لو ترغب
        amount = input('كم عدد اليوزرات ؟')
        amount = int(amount)

        length2 = 3
        length2 = int(length2)

        for password in range(amount):
            password = ''
            for item in range(3):
                password = ''
            for item in range(3):
                password += random.choice(chars2)

            bc= password + uesr


            print(bc)
            with open('user.txt', 'a') as x:
                x.write(bc + '\n')
if sa == "2":
    print("مكانها؟")
    print("1| .***")
    print("2| *.**")
    print("3| **.*")
    print("4| ***.")
    da = input("اختار:")
    if da == "1":
        uesr = '.'  # اليوزر المراد التخمين عليه بين النقطتين اكتبه
        chars2 = 'qwertyuiopasdfghjklzxcvbnm0123456789'  # ارقام واحرف لو ترغب
        amount = input('كم عدد اليوزرات ؟')
        amount = int(amount)

        length2 = 3
        length2 = int(length2)

        for password in range(amount):
            password = ''

            for item in range(length2):
                password = ''
            for item in range(length2):
                password += random.choice(chars2)
            bb= uesr + password
            print(bb)
            with open('user.txt', 'a') as x:
                x.write(bb + '\n')
    if da == "2":
        uesr = '.'  # اليوزر المراد التخمين عليه بين النقطتين اكتبه
        chars2 = 'qwertyuiopasdfghjklzxcvbnm0123456789'  # ارقام واحرف لو ترغب
        amount = input('كم عدد اليوزرات ؟')
        amount = int(amount)

        length2 = 3
        length2 = int(length2)

        for password in range(amount):
            password = ''

            for item in range(length2):
                password = ''
            for item in range(length2):
                password = random.choice(chars2)
            for item in range(2):
                password1 = ''
            for item in range (2):
                password1 += random.choice(chars2)
            ba = password + uesr + password1


            print(ba)
            with open('user.txt', 'a') as x:
                x.write(ba +'\n')

    if da == "3":
        uesr = '.'  # اليوزر المراد التخمين عليه بين النقطتين اكتبه
        chars2 = 'qwertyuiopasdfghjklzxcvbnm0123456789'  # ارقام واحرف لو ترغب
        amount = input('كم عدد اليوزرات ؟')
        amount = int(amount)

        length2 = 3
        length2 = int(length2)

        for password in range(amount):
            password = ''

            for item in range(2):
                password = ''
            for item in range(2):
                password += random.choice(chars2)
            for item in range(1):
                password1 = ''
            for item in range(1):
                password1 += random.choice(chars2)
            bd = password + uesr + password1

            print(bd)
            with open('user.txt', 'a') as x:
                x.write(bd + '\n')
    if da == "4":
        uesr = '.'  # اليوزر المراد التخمين عليه بين النقطتين اكتبه
        chars2 = 'qwertyuiopasdfghjklzxcvbnm0123456789'  # ارقام واحرف لو ترغب
        amount = input('كم عدد اليوزرات ؟')
        amount = int(amount)

        length2 = 3
        length2 = int(length2)

        for password in range(amount):
            password = ''
            for item in range(3):
                password = ''
            for item in range(3):
                password += random.choice(chars2)

            bc= password + uesr


            print(bc)
            with open('user.txt', 'a') as x:
                x.write(bc + '\n')
if sa == "3":
        uesr = '.'  # اليوزر المراد التخمين عليه بين النقطتين اكتبه
        chars2 = 'qwertyuiopasdfghjklzxcvbnm0123456789'  # ارقام واحرف لو ترغب
        amount = input('كم عدد اليوزرات ؟')
        amount = int(amount)
        length2 = 3
        length2 = int(length2)

        for password1 in range(amount):
            password1 = ''
            for item in range(length2):
                password1 = ''
            for item in range(length2):
                password1 += random.choice(chars2)
            password35="."+password1



            password2 = ''

            for item in range(length2):
                password2 = ''
            for item in range(length2):
                password2 = random.choice(chars2)
            for item in range(2):
                password3 = ''
            for item in range (2):
                password3 += random.choice(chars2)
            password27=password2+"."+password3


            password4 = ''

            for item in range(2):
                password4 = ''
            for item in range(2):
                password4 += random.choice(chars2)
            for item in range(1):
                password5= ""
            for item in range(1):
               password5+=random.choice(uesr)
            for item in range(1):
               password99 = ''
            for item in range(1):
               password99 += random.choice(chars2)
               password9 = password4+password5+password99



            useer = '_'  # اليوزر المراد التخمين عليه بين النقطتين اكتبه
            chars2 = 'qwertyuiopasdfghjklzxcvbnm0123456789'  # ارقام واحرف لو ترغب

            for password109 in range(amount):
                password109 = ''
                for item in range(length2):
                    password109 = ''
                for item in range(length2):
                    password109 += random.choice(chars2)
                password350 = "_" + password109

                password20 = ''
                for item in range(length2):
                    password20 = ''
                for item in range(length2):
                    password20 = random.choice(chars2)
                for item in range(2):
                    password30 = ''
                for item in range(2):
                    password30 += random.choice(chars2)
                password270 = password20 + "_" + password30

                password40 = ''

                for item in range(2):
                    password40 = ''
                for item in range(2):
                    password40 += random.choice(chars2)
                for item in range(1):
                    password50 = ""
                for item in range(1):
                    password50 += random.choice(useer)
                for item in range(1):
                    password990 = ''
                for item in range(1):
                    password990 += random.choice(chars2)
                    password90 = password40 + password50 + password990

                password60 = ''
                for item in range(3):
                    password60 = ''
                for item in range(3):
                    password60 += random.choice(chars2)
                    password100 = password60 + "_"

            mylist = [password9,password27,password35,password100,password90,password270,password350]
            passwordff=""
            ddd = passwordff+random.choice(mylist)
            print(ddd)
            with open('user.txt', 'a') as x:
                x.write(ddd + '\n')

if sa =="4":
    uesr = ''  # اليوزر المراد التخمين عليه بين النقطتين اكتبه
    chars2 = 'qwertyuiopasdfghjklzxcvbnm1234567890._'  # ارقام واحرف لو ترغب
    amount = input('كم عدد اليوزرات ؟')
    amount = int(amount)

    length2 = input('ما طول اليوزر الي تبيه؟')
    length2 = int(length2)

    for password in range(amount):
        password = ''

        for item in range(length2):
            password = ''
        for item in range(length2):
            password += random.choice(chars2)

        print(password)
        with open('user.txt', 'a') as 
