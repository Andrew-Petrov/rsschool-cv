## Andrew Petrov   

### Contact Info
1. **email** (*first*): theprivetandreybest@gmail.com  
2. **email** (*second*): theprvetandreybest@yandex.ru
3. **phone number**: 8 950 044 23 91  

### Goals and desires:
* to see the implementation of my actions in practice
* to create softwares, which will be used by people and help them solve problems
* to be a comprehensively developed programmer - do not stop at software or websites, develop in the field of design and creation of graphic models, applications, games
* learn, how to choose the language that is most suitable for the task at hand
 
### Important things for me:
 * self-education is the main path to knowledge
 * desire and ability to find non-standard solutions to different tasks
 * interested in non-standard math tasks
 * base knowledje of javascript 

###  Skills:
- [x] good knowlewledge of *C/C++*
- [x] learning *openGl*
- [x] base knowlewledge of *javascript*, *CSS*, *PHP*, *HTML*
- [x] *matlab* knowledge
- [x] good knowledge in *math*

### My code:

*Functions that help find the real number among the rest of the characters in C++*:
(with the study and use of a function that has features that complicate the code)

**action subfunction**:
```c++
float perevod(string vvod)
{
    setlocale(0, "C"); 
    float chislo = float(atof(data(vvod)));
    setlocale(LC_ALL, "Russian"); // Использование русского алфавита

    return chislo;
};
```

**result function**:

```c++
float PROinput2()
{

    while (true) 
    {
        string vvod; 
        cin >> vvod; 
        
        for (int i = 1; vvod[i] != '\0'; i++)
        {
            if (vvod[i] == ',')
            {
                vvod[i] = '.';
                break;
            }
        }

        float chislo = perevod(vvod);

        int k = 0; // проверка ввода символа
        int i = 0;
        if (vvod[0] == 45)
        {
            i = 1;
        }
        for (i; i < strlen(data(vvod)); i++)
            if ((vvod[i] <= 57) && (vvod[i] >= 48) || (vvod[i] == 46))
            {
                k = 0;
            }
            else
            {
                k = 1;
                break;
            }

        if (k == 0)
        {
            return chislo;
        }
        else
        {
            cout << "   Вы ввели неверное число. Попробуйте снова!" << endl;
            cout << "   Введите число: ";
        }

    }
};
```

### Experience:
- [x] Project on matlab for univercity subject
- [ ] Project on C++ for univercity subject

### Education: 

1. **Cources**:

* stepic
* epam
* english course

2. **online learning**: 
* youtube cource C++
* English youtube cource

3. **education**

* studing at the university in the direction of software engineering
    - matlab
    - C/C++
    - openGL

### English:
- [x] non practice, only conversation with friends or in class, whatching films in english

