# python3
 1. Percabangan If
 
  Source Code
  
  is_day =True
  
  is_night = False
  
  if is_day:
  
    print("Selamat berakhir pekan")
    
  elif is_night:
  
    print("selamat suka suka")
    
  else :
  
    print("selamat siang")
    
  print("selamat menikmati hari dengan tugas")
  
  Vs code dan Output
  ![p11](https://user-images.githubusercontent.com/92987122/140687112-f64ec85e-a746-4902-8718-49c7e510fc62.png)

 2. Operator perbandingan
  
  Source Code
  
  result = 4 > 3
  
  print(result)
  
  # hasilnya true karna 4 lebih besar dari 3

  grade = 6.5

  if grade >= 8:
  
    print("nilai kamu A")
    
  elif grade >=7:
  
    print("nilai kamu B")
    
  elif grade >=6:
  
    print("nilai kamu C")
    
  else:
  
    print("Silahkan belajar lebih baik lagi")
    
  Vs code dan Output
  ![p12](https://user-images.githubusercontent.com/92987122/140687177-c1b98d27-2861-491b-8e07-c8b5d287828a.png)

 3. Operator logika
 
   Source Code
   
   name ="cece"
   
   by_pass_validation = True
   
   if len(name) > 10 or by_pass_validation:
   
    print("welcome")
    
   else:
   
    print("nama terlalu pendek")
    
   Vs code dan Output
   ![p13](https://user-images.githubusercontent.com/92987122/140687287-aa6d0b8f-e6af-461a-b597-2c0948ad402b.png)

 4. perulangan while
  
  Source Code
  
  index = 1

  while index <= 5:
  
    print("*" * index)
    index += 1

print("finish")

  Vs code dan Output
  ![p14](https://user-images.githubusercontent.com/92987122/140687348-d197354f-f31d-4911-ba67-a9c71bac99ef.png)

 5. game tebak angka 
  
  Source Code
  
  trying = 0
  
  secret_number = 4
  
  limit = 3

  while trying < limit:
  
    guess_number = input("masukan angka (1-6) : ")
    
    guess_number = int(guess_number)

    if guess_number == secret_number:
    
        print("selamat kamu menang")
        
        break

  trying += 1
  
  Vs code dan Output
  ![p15](https://user-images.githubusercontent.com/92987122/140687442-0ed5a518-9622-4ddc-a18b-8c92d4d8c50b.png)

 6. aplikasi kalkulator
 
  Source Code 
  
  # (+ - * / exit)
  
command = ""

while command !="exit" :

    command = input ("Perintah : ")

    if command == "exit" :
    
        break

    if command != "+" and command != "-" and command != "*" and command != "/" :
    
        print("perintah tidak dikenali")
        
        continue

    a = int (input("angka pertama :"))
    
    b = int (input("angka kedua :"))

    if command =="+":
    
        result = a +b
        
    elif command == "-":
    
     result = a -b
     
    elif command == "*":
    
     result = a *b
     
    elif command == "/":
    
     result = a /b

    print(f"hasil : {result}")

print("terimakasih sudah menggunakan aplikasi kami")

  Vs code dan Output
  ![p16](https://user-images.githubusercontent.com/92987122/140687482-68f9a1d3-3e4f-4c3b-953b-a45a2eeb9c69.png)
