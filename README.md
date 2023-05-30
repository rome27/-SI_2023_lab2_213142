# SI_2023_lab2_213142

Ognen Romevski 213142

# Control Flow Diagram
![cfg](213142CFG.png)

# Цикломатска комплексност

Кодот има цикломатска комплексност од 11, кој се добива преку броење на регионите.

# Every branch

Случај 1: user==null
Случај 2: password = null
Случај 3: email = null
Случај 4: email нема @ или .
Случај 5: нема specialCharacters во password
Случај 6: password.length < 8
Случај 7: има " " во password
Случај 8: го има email во allUsers

# Multiple conditions

1. user = null
2. user != null, user.getpassword = null
3. user != null, user.getpassword = null, user.getemail = null
4. user != null, user.getpassword = null, user.getemail = null