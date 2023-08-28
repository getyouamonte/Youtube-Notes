# Ethnical Hacking In 15Hours


    Url: https://www.youtube.com/watch?v=3FNYvj2U0HM&t=10814s

### Pimp My Kali  (3:14:00)





## Intro To Python


##### Strings (3:43:00)

    mkdir (directoryname)
        Make a directory and change into directory

    mousepad (filename.py)&
        the & command keeps terminal open while mousepad is open


#######3:46:00 Hello World command


        In the script enter:
            
            #!/bin/python3

            #Print string
            print("Hello, world!")
            print('Hello, world!')
            print("""This string runs
            multiple lines!""") #triple quote for multi-line
            print("This string is "+"awesome!") #We can also concatenante
            print('\n') #new line
            print('Test that new line out.')
            )

![Alt text](<Screenshot 2023-07-31 at 6.20.04 PM.png>)




##### Math

        In the Script:

        #!/bin/python3

        #Math
        print(50 + 50) #add
        print(50 - 50) #subtract)
        print(50 * 50) #multiply
        print(50 / 50) #divide
        print(50 + 50 - 50 * 50 / 50) #PEMDAS
        print(50 ** 2) #exponents
        print( 50 % 6) #modulo - takes what is left over
        print(50 / 6) #division with remainder (or a float)
        print (50 // 6) #no remainder

##### Variables & Methods (3:57:00)

        In the Script:

        quote = "All is fair in loce and war."
        print(quote)

        print(quote.upper()) #uppercase
        print(quote.lower()) #lowercase
        print(quote.title()) #title case
        print(len(quote)) #counts characters and spaces

        name = "Heath" #string
        age = 33 #int
                    [#int stands for integer]
        gpa = 3.7 #float - has a decimal

        print(int(age))
        print(int(30.1))
        (print(int(30.9)) #Will it round NO.

        print("My name is " + = name + " and I am " + str(age) + " years old.")

        age += 1
        print(age)

        birthday = 1
        age += birthday
        print(age)

###### Functions (4:07:00)

        In the script:

        def who_am_i(): #this is a function without parameters
            name = "Heath" #local variable
            age = 30
            print(("My name is " + = name + " and I am " + str(age) + " years old.")

        who_am_i()
        
        def ass_one_hundred(num):
            print(num + 100)

        add_one_hundred(100)

        def add(x,y):
            print(x + y)

        add(7,7)

        def multiply9x,y):
            return x * y

        multiply(7,7)
        print(multiply(7,7))

        def square_root(x):
            print(x ** .5)

        square_root(64)

        def nl(): #new line
            print('\n')

##### Boolean Expressions and Relational Operators (4:16:00)

        
        In the script:

        #BOOLEAN EXPRESSIONS (TRUE OR FALSE)

        bool1 = True
        bool2 = 3*3 == 9
        bool3 = 3*3 != 9

        print(bool1,bool2,bool3,bool4)
        print(type(bool1))

        bool5 = "True"
        print(type(bool5))

        nm()
        #RELATIONAL AND BOLEAN OPERATORS
        greater_than = 7 > 5
        less_than = 5 < 7
        greater_than_equal_to = 7 >= 7

        test_and = (7 > 5) and (5 < 7) #True
        test_and2 = (7 > 5) and (5 > 7) #False
        test_or = (7 > 5) or (5 < 7) #True
        test_ot2 = (7 > 5) or (5 > 7) #True

        test_not = not True #False

##### Conditional Statements - if/else (4:25:00)

def drink(money):
    if money >= 2:
        return "You've got yourself a drink!"
    else:
        return "No drink for you!"

print(drink(3))
print(drink(1))

def alchol(age,money):
    if (age >= 21) and (money >= 5):
        return "We;re getting a drink!"
    elif (age >= 21) and (money < 5):
        return "Come back with more money."
    elif (age < 21) and (money >= 5):
        return "Nice try,kid!"
    else:
        return "You're too young and too poor."
    
print(alcohol(21,5))
print(alcohol(21,4))
print(alcohol(20,5))
print(alcohol(20,4))

##### List - Have brackets (4:31:00)

movies = ["Monsters Inc", "The Hangover" , "Monsters House"]

print(movies[1]) #returns the second item in the list
print(movies[0]) #returns first item on list
print(movies[1:3]) #returns the first index number given right until the last number given, but not include the last number, if you go 1 to 3 it will print 1 and 2.
print(movies[1:])
print(movies[:1]) #this prints list number 1 and anything before 
print(movies[-1]) #This will return last item in list

print(len(movies)) #counts items in the list
movies.append("JAWS")
print(movies) #sppends to the end of the list

movies.insert(2, "Hustle") #Adds hustle into 2
print(movies)

movies.pop() #removes the last item
print(movies)

movies.pop0() #removes the first item
print(movies)

amber_movies = ['Just go with it', '50 first dates']
our_favorite_movies = movies + amber_movies #Combines list
print(our_favorite_movies)

grades = [["Bob", 82], ["Alice", 90], ["Jeff", 73]]
bobs_grade = grades[0][1]
print(bobs_grade)
grades[0][1] = 83 #change bobs grades
print(grades)

#####Tuples - Do not change, (4:44:00)
grades = ("a", "b", "c", "d", "f")

print(grades[1])

##### Looping - start to finish of an iterate (4:46:00)

vegetables = ["cucumber", "spinach", "cabbage"]
for x in vegetables:
    print(x)


###### While loops - execute as long as True
i = 1

while i < 10:
    print(i)
    i += 1


##### Advanced Strings (4:50:00)

my_name = "Heath"
print(my_name[0]) #first letter
print(my_name[-1]) #last letter

sentence = "This is a sentence"
print(sentence[:4])
print(sentence.split()) #delimeter - default is a space .... says we will take something ans split it like that

sentence_split = sentence.split()
sentence_join = ' '.join(sentence_split)
print(sentence_join)

quote = "He said, give me all your money"
print(quote)
quote = "He said, \"give me all your money\"
print(quote)

too_much_space + "            hello           "
print(too_much_space.strip()) #deletes all space

print("A" in "Apple") #True
print("a" in "Apple") #False because of case sensitivity


letter = "A"
word = "Apple"
print(letter.lower() in word.lower()) #improved

movie = "The Hangover"
print(My favorite movie is {}.".format(movie)) #string format method
print("My favorite movie is %s." %movie)
print(f"My favorite movie is {movie},")

##### Dictionaries - key/value pairs (5:03:00)

drinks = {"White Russian": 7, "Old Fashioned": 10, "Lemon Drop": 8} #drink is key, price is value
print(drinks)

employees = {"Finance": ["Bob", "Linda", "Tina"], "IT": ["Gene", "Louise", "Teddy"], "HR": ["Jimmy Jr.", "Mort"]}
print(employees)

employees['Legal'] = [Mr. Frond"] #adds new key:value pair
print(employees)

employees.update({"Sales": [Andie", :ollie:]}) #adds new key:value pair
print(employees)

drink['White Russin'] = 8 #updates drink price
print(drinks)

print(drinks.get("White Russian))


##### Importing Modules - Importing is Important (5:10:00)

Create a new files

    In the Script:

    #!/bin/python3
    import sys #system functions and parameters
    import datetime import datetime as dt #import with alias


    print(sys.version)
    print(datetime.now())
    print(dt.now)) $new after alias was inserted



##### Sockets - Used to make a connection between port and IP addresses (5:15:00)

Dont name it socket.py
Create new files

    In the script:

    #!/bin/python3

    import socket

    HOST = '127.0.0.1'
    PORT = 7777

    s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) #af_inet is ipv4, sock_stream is a port
    s.connect((HOST,PORT))


##### Builidng Port Scanner (5:23:00)

    create a script
    
    mousepad scanner.py&

    In the script:

    #!/bin/python3

    import sys
    import socket
    from datetime import datetime

    #Define our target
    if len(sys.argv) == 2:
        target = socket.gethostbyname(sys.argv[1]) #Translate hostname to IPv4
    else:
        print("Invalid amount of arguments.")
        print("Syntax: python3 scanner.py <ip>")

    #Add a pretty banner
    print("-" * 50)
    print("Scanning target: "+target)
    print("Time started: "+str(datetime.now()))
    print("-" * 50)

    try: 
        for port in range(50,85) #attempt to scan home router and usally dns open on that along with port 80's)
            s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) #setting the variable to gather IPV4 address
            socket.setdefaulttimeout(1)
            result = s.connect_ex((target,port)) #target and port both being identified in earlier syntax
            if result == 0:
                print(f"Port [port] is open") #if port is open it will show result if not it will close and start over
            s.close()

    except KeyboardInterrupt:
        print(\nExiting program.")
        sys.exit()

    except socket.gaierror:
        print("Hostname could not be resolved.")
        sys.exit()

    except socket.error:
        print("Could not connect to server.")
        sys.exit()

###### Run the command to activate script

    python3 scanner.py <Use IP Address>

    You need an IP address has to have ports between 50-85 open so a result comes up.

    The command to run script

    python3 scanner.py 192.168.4.1

    This script will show you what ports are open.


##### User Input (5:42:00)

        Create a script

            nousepad input.py&

        In the script


            #!/bin/python3

            name = input("Enter your name: ")
            drink = input("Whats your favorite drink?: ")
            print("Hello "+name+"!" Have a "+drink".")


        New Script (Build Calculator)

            #!/bin/python3

            x = float(input("Give me a number: "))
            o = input("Giv mr an operator: ")
            y = float(input("Give me yet another number: "))
            
            if o == "+":
                print(x + y)
            elif o == "-":
                print(x - y)
            elif o == "/":
                print(x / y)
            elif o == "*":
                print (x * y)
            elid o == "**" or o == "^":
                print(x ** y)
            else:
                print("Unknown operator.")

        To run command:
            python3 input.py



##### Reading and writing Files (5:50:00)

        Create the File

            mousepad months.txt

        In the script:
            January
            Febuary
            March
            April
            May
            June 
            July
            August
            September
            October
            November
            December

        Create new python file
            
            mousepad readwrite.py&

        In the script:

            #!/bin/python3

            months = open('months.txt')

            print(months.read())
            print(months.readline()) #reads line by line
            print(months.readlines()) #reads all lines

            for months in months:
                print(month.strip()) #prints the months but strips the line spacing

            months.close()


        New Script:

        #!/bin/python3

        days = open('days.text' , "w") # R is read , W is write which overwrties, A is append which adds to the file

        days.write("Monday")

        days.close()


##### Classes and Objects (6:00:00)


        Create Python
            mousepad Employees.py&

        In the script:

            class Employees:

                def_init_(self, name, department, role, salary, years_employed):
                    self.name = name
                    self.department = department
                    self.salary = salary
                    self.years_employed = years_employed

                def eligible_for_retirement(self):
                    if self.years_employed >= 20:
                        return True
                    else:
                        return False


        Open another Mousepad:

            mousepad ouremployees.py&


        In the script:

            #!/bin/python3

            from Employees import Employees

            el = Employees("Bob", "Sales", "Director of Sales", 100000, 20)
            e2 = Employees("Linda", "Executive", "CIO", 150000, 10)

            print(e1.name)
            print(e2.role)
            print(e1.eligible_for_retirement())

            #Building out own classes and linking them together.




##### Building a shoe budget (6:08:00)
Using classes and objects

        Create mousepad

            mousepad Shoes.py&


        In the script:

            class Shoes:
                def __init__(self, name, price):
                    self.name = name
                    self.price = float(price)

                def budget_check(self, budget):
                    if not isinstance(budget, (int, float)):
                        print('Invalid entry. Please enter a number.')
                        exit()

                def change(self, budget):
                    return (budget - self.price)

                def buy(self, budget):
                    self.budget_check(budget)

                    if budget >= self.price:
                        print(f'You can cop some {self.name}')

                        if budget == self.price:
                            print('You have exactly enough money for these shoes.')
                        else:
                            print(f'You can buy these shoes and have $ {self.change(budget)} left over')

                        exit('Thanks for using our shoe budget app!')

    Create another python script

        shoeperclass.py

    In the script:

        #!/bin/python3

        from Shoes import Shoes

        low = Shoes('And ls', 30)
        medium = Shoes('Air Force 1s', 120)
        high = Shoes('Off Whites', 400)

        try:
            shoe_budget = float(input('What is your shoe budget? '))
        except ValueError:
            exit('Please enter a number')

        for shoes in [high, medium, low]: #ensure it goes from high to low
            shoes.buy(shoe_budget)


    To run script

        python3 shoepurchase.py




##### 5 Stages of Ethnical Hacking (6:22:00)


            Stage 1: Reconnaissance (6:28:00)

                Active  
                
                Passive

            Stage 2: Scanning and Enumeration

                Using toos like Nmap, Nessus, Nikto, Etc

            Stage 3: Gaining Access (Exploitation)

                Actually gaining access into the system

            Stage 4: Maintaining Access

                If they shut down their computer how do you keep or maintain access in all levels

            Stage 5: Covering Tracks

                Delete any logs , malware that you uploaded, any accounts created essentially clean up.



###### Passive Recon Overview (6:28:00)

        Physical/Social

            Location Information:

                Satellite Images

                Drone Recon

                Building layout (badge readers, break areas, security, fencing)

            Job Information:

                Employees (name, job title, phone number, manager,etc.)

                Pictures (badge photos, desk photos, computer photos)

        Web/Host

            Target Validation

                WHOIS
                nslookup
                dnsrecon

            Finding Subdomains

                Google Fu 
                dig 
                Nmap
                Sublist3r 
                Bluto 
                crt.sh
                etc

            Fingerprinting

                Nmap
                Wappalyzer 
                WhatWeb
                BuiltWith
                Netcat

            Data Breaches 

                HaveIBeenPwned 
                Breach-Parse 
                WeLeakInfo

### Gathering Information

###### Identifying our Target (6:35:00)

        Bug Crowd - Bug Bounty Program

        *Ensure you are still in scope when picking programs and hacking

        When picking the program read the in scope portion to ensure you say in range. 

        Look at Out of scope which shows you what you cannot attack.

        Biggest focus is on information gathering.

###### Discovering Email Addresses (6:39:00)

    Finding Emails and information

        hunter.io - lets you find email addresses in seconds to connect with the poeple that matter for your business

            Type in the company or domain you are doing recon with on the website and it will give you email addresses and based off of sources and also shows most common pattern on email addresses. 
            It will show you what departments and are location based.

            Sign up with gmail address.

        Phonebook.cz

            List all domains, email addresses or URLS for given input domain. Wildcards such as .gov.uk are allowed.

            Searching 25 billion reccords not a gurantee its all valid 

            Type domain in search engine and it will showcase a list of emails associated with the domain search or the company.

        Voilanobert.com

            Same as email searches above.

        Clearbit Connect (Chrome Exension)

            Has to be used in Chrome

            Discovers some that others didn't discover offers location and in some cases linkedin profile

    Email Verification

        Email Hippo

            https://tools.verifyemailaddress.io

            Will provide false positives , but its purpose is to verify email addresses in real time.


        Email Checker

            https://email-checker.net/validate

        
    Forgot Password

        Google

            *Do not underestimate forgot password

            When typing in email in gmail

            click forgot password when it ask for last password remembered. Click for another way and it will give you an alternate where google could send the email.

            You can use that to verify a link between two accounts identifying with the same email address. Same first character and same domain name.

###### Breached Credentials (6:55:00)

    https://github.com/hmaverickadams/breach-parse

###### Hunting Breached Credentials (7:02:00)

    https://Dehashed.com (Paid platform)

        Grants the ability to search by email address, username , IP, address, phone, VIN, Domain Scan

    Hashes.org

        Finding hashes on dehashed and atempting to crack them there.

        There is a guthib adobe data base that you can type hashes in and see if it finds anything


#### Part 2 https://www.youtube.com/watch?v=sH4JCwjybGs&t=2656s


###### Hunting Sub Domains Pt 1 (00:00:30)

Email : *.tesla.com

* = a wildcard

###### sublist3r

    tool in linux to find sub domains and 3rd and 4th level domains

    To Install:

            apt install sublist3r

        Command:

            sublist3r -d tesla.com

        For Help:

            sublist3r -h 



###### crt.sh

    Similar to sublister uses certificate fingerprinting / certificates that have been registered 


        %.tesla.com

        % = serves as wildcard

    After typing in looking through certificates shows you different levels of domains and sub domains.



###### Hunting Sub Domains Pt 2 (00:05:54)


###### OWASP Amass

    Challenge get Amass installed and see how many more subdomains you can find vs sublist3r


        https://github.com/owasp-amass/



###### Tomnomnom 

    Takes a list of domains and probe for working HTTP and HTTPS servers

        https://github.com/tomnomnom

##### Identifying Website Techonologies (00:10:45)

    What a website is built with

    Built With

        Search in google builtwith

            https://builtwith.com/

            looks at what type of tech the domain is running. Scroll down to frameworks/ content delivery network/ content management systems/ email hosting / Etc

    Wappalyzer

        Search in google and type in wappalyzer for firefox

        https://addons.mozilla.org/en-US/firefox/addon/wappalyzer/

        Not much information as built with , more of an active type of reconassinse but still passive because you're not doing anything out of the normal.

        More of a condensed service and gives you upfront information aside from all the information included in builwith.

    whatweb 
    (built in kali)

        Command:

            whatweb https://tesla.com

            gives some infromation not as pretty of a layout.
            It specifies more detailed versions of tools being used.

            Ex. Wappalyzer specificed PHP was being used whilst whatweb gave a version number such as 7.3.7.

##### Gathering Information with Burp Suite (00:18:08)

    BurpSuite

        Web proxy capable of intercepting web traffic

        Set up firefox for utilizing burp suite

            Go to preferences > settings > manual proxy configuration > HTTP Proxy: 127.0.0.1 Port 8080 > Check "Use this proxy server for all protocols > click OK

            Click new tab > go to https://burp > click allow > click on CA certificate > Save the file > go back into preferennces on firefox (about:preferences) > click on privacy and security > scroll all the way down to bottom > under certificates > click view certificates > Import > select cacert.dr file > check both check boxes > click ok > 

            When going to a web browser you will now see page takes a while to load > click into burp suite > Proxy should be highlighted > click proxy > and now you are able to analyze all the traffic being analyzed through your webpage.

##### Google Fu (00:27:08)

    Google Search Syntax

    Url : https://ahrefs.com/blog/google-advanced-search-operators/

    Examples

        1. **Basic Search:**
        - Syntax: `keyword`
        - Example: `cat videos`
        - Usage: This is the most basic search syntax. It looks for web pages containing the specified keyword. It's useful when you want to find general information related to a particular topic.

        2. **Phrase Search:**
        - Syntax: `"search phrase"`
        - Example: `"best pizza in New York"`
        - Usage: By using quotes, you can search for an exact phrase. This is handy when you want to find pages that contain the exact words in the same order as you typed them.

        3. **Exclude Keywords:**
        - Syntax: `-keyword`
        - Example: `apple -fruit`
        - Usage: If you want to exclude certain results containing a specific keyword, use the minus sign (-) followed by the keyword you wish to exclude.

        4. **Site-specific Search:**
        - Syntax: `keyword site:example.com`
        - Example: `iPhone site:apple.com`
        - Usage: This syntax allows you to search for content only within a particular website or domain. It's helpful when you want to limit your search to a specific site.

        5. **File Type Search:**
        - Syntax: `filetype:pdf`
        - Example: `python tutorial filetype:pdf`
        - Usage: Use this to find specific file types on the web. Replace "pdf" with the desired file extension.

        6. **Related Websites:**
        - Syntax: `related:example.com`
        - Example: `related:wikipedia.org`
        - Usage: This syntax shows web pages that Google considers similar to the specified website.

        7. **OR Operator:**
        - Syntax: `keyword1 OR keyword2`
        - Example: `cats OR dogs`
        - Usage: Use the OR operator to search for pages containing either of the specified keywords.

        8. **Info About a Website:**
        - Syntax: `info:example.com`
        - Example: `info:amazon.com`
        - Usage: This shows information about the specified website, including cached versions, similar sites, and indexed pages.

        9. **Wildcard Search:**
        - Syntax: `keyword * keyword`
        - Example: `life * like a box of chocolates`
        - Usage: The asterisk (*) acts as a wildcard placeholder, and Google fills in the blank with relevant words to generate results.

        10. **Define a Word:**
            - Syntax: `define:word`
            - Example: `define:serendipity`
            - Usage: This syntax provides definitions of the specified word from various sources.

        11. **Number Range Search:**
            - Syntax: `number..number`
            - Example: `iPhone $500..$1000`
            - Usage: You can use this to search for results within a specified numeric range.

        12. **Cache Search:**
            - Syntax: `cache:example.com`
            - Example: `cache:google.com`
            - Usage: This shows the latest cached version of the specified website.

        13. **Intitle Search:**
            - Syntax: `intitle:keyword`
            - Example: `intitle:OpenAI`
            - Usage: This searches for pages with the specified keyword in their titles.

        14. **Inurl Search:**
            - Syntax: `inurl:keyword`
            - Example: `inurl:forum`
            - Usage: This looks for URLs containing the specified keyword.

        15. **Phone Number Lookup:**
            - Syntax: `phonebook:John Doe`
            - Example: `phonebook:John Doe`
            - Usage: This syntax helps find phonebook listings related to the specified name.

        16. **Time-based Search:**
            - Syntax: `after:yyyy-mm-dd`
            - Example: `iPhone release date after:2023-01-01`
            - Usage: It allows you to find results after a specific date.

        17. **Link Search:**
            - Syntax: `link:example.com`
            - Example: `link:wikipedia.org`
            - Usage: Use this to find pages that link to the specified URL.

        18. **Map Search:**
            - Syntax: `map:location`
            - Example: `map:New York City`
            - Usage: It displays a map of the specified location.

        19. **Stocks Information:**
            - Syntax: `stocks:stock_symbol`
            - Example: `stocks:AAPL`
            - Usage: This shows information about the specified stock symbol.

        20. **Weather Information:**
            - Syntax: `weather:location`
            - Example: `weather:London`
            - Usage: It displays current weather information for the specified location.

        21. **Related Images:**
            - Syntax: `related:images.example.com`
            - Example: `related:images.unsplash.com`
            - Usage: It shows image results similar to the specified image source.

        22. **Related News:**
            - Syntax: `related:news.example.com`
            - Example: `related:news.bbc.co.uk`
            - Usage: It displays news results related to the specified news source.

        23. **Movie Showtimes:**
            - Syntax: `movie:movie_title`
            - Example: `movie:Inception`
            - Usage: This provides showtimes for the specified movie.

        24. **Book Search:**
            - Syntax: `book:book_title`
            - Example: `book:"To Kill a Mockingbird"`
            - Usage: It helps find pages related to the specified book title.

        25. **Movie Search:**
            - Syntax: `movie:movie_title`
            - Example: `movie:The Avengers`
            - Usage: It retrieves information about the specified movie.

        26. **Stock Market Data:**
            - Syntax: `stock:stock_symbol`
            - Example: `stock:GOOGL`
            - Usage: It displays stock market data for the specified stock symbol.

        27. **Package Tracking:**
            - Syntax: `package:tracking_number`
            - Example: `package:1234567890`
            - Usage: Use this to track a package by its tracking number.

        28. **Location-based Search:**
            - Syntax: `near:location`
            - Example: `restaurants near Central Park`
            - Usage: It shows results related to the specified location.

        29. **Related Videos:**
            - Syntax: `related:videos.example.com`
            - Example: `related:videos.youtube.com`
            - Usage: It shows video results similar to the specified video source.

        30. **Calculator:**
            - Syntax: `calculator expression`
            - Example: `calculator 2+2`
            - Usage: Use this to perform simple calculations directly in Google's search box.

        31. **Time Zone Lookup:**
            - Syntax: `time:location`
            - Example: `time:London`
            - Usage: It displays the current time in the specified location.

        32. **Currency Conversion:**
            - Syntax: `currency amount1 to amount2`
            - Example: `currency USD to EUR`
            - Usage: This converts the specified currency from one amount to another.

        33. **Unit Conversion:**
            - Syntax: `unit amount1 to amount2`


            - Example: `unit meters to feet`
            - Usage: It converts the specified unit from one amount to another.

        34. **Synonym Search:**
            - Syntax: `~keyword`
            - Example: `~cheap laptops`
            - Usage: It finds results related to synonyms of the specified keyword.

        35. **File Search:**
            - Syntax: `filetype:extension keyword`
            - Example: `filetype:pdf getting started guide`
            - Usage: It searches for a specific file type containing the specified keyword.

        36. **Hashtag Search:**
            - Syntax: `#hashtag`
            - Example: `#travel`
            - Usage: It shows social media posts containing the specified hashtag.

        37. **Movie Reviews:**
            - Syntax: `reviews:movie_title`
            - Example: `reviews:Avatar`
            - Usage: It displays reviews for the specified movie.

        38. **Stocks Comparison:**
            - Syntax: `stocks:stock1 vs stock2`
            - Example: `stocks:AAPL vs MSFT`
            - Usage: Use this to compare information between two stock symbols.

        39. **Flight Information:**
            - Syntax: `flight:flight_number`
            - Example: `flight:AA101`
            - Usage: It shows real-time flight information for the specified flight number.

        40. **Movie Trailers:**
            - Syntax: `movie:movie_title trailer`
            - Example: `movie:Interstellar trailer`
            - Usage: It displays trailers for the specified movie.

        41. **Define a Term from a Specific Website:**
            - Syntax: `site:example.com define:term`
            - Example: `site:wikipedia.org define:algorithm`
            - Usage: This finds definitions of a term from a specific website.

        42. **Search for Specific File Types on a Website:**
            - Syntax: `site:example.com filetype:extension keyword`
            - Example: `site:github.com filetype:pdf machine learning`
            - Usage: It searches for a specific file type containing the specified keyword on a particular website.

        43. **Search for Titles Only:**
            - Syntax: `intitle:keyword`
            - Example: `intitle:"How to meditate"`
            - Usage: This looks for pages with the specified keyword in their titles.

        44. **Search for URLs Only:**
            - Syntax: `inurl:keyword`
            - Example: `inurl:blog`
            - Usage: It finds URLs containing the specified keyword.

        45. **Search Social Media Posts:**
            - Syntax: `keyword site:twitter.com`
            - Example: `Google site:twitter.com`
            - Usage: It shows results containing the specified keyword from a particular social media site.

        46. **Exclude a Specific Site:**
            - Syntax: `keyword -site:example.com`
            - Example: `iPhone -site:wikipedia.org`
            - Usage: This excludes results from a specific website when searching for the specified keyword.

        47. **Search for Specific File Types on All Sites:**
            - Syntax: `filetype:extension keyword`
            - Example: `filetype:docx proposal`
            - Usage: It searches for a specific file type containing the specified keyword across all websites.

        48. **Find Results in the Past Hour/Day/Week:**
            - Syntax: `keyword date_range`
            - Example: `hurricane news last 24 hours`
            - Usage: This searches for results within a specific date range.

        49. **Search for Content in Title and Body:**
            - Syntax: `intitle:keyword OR intext:keyword`
            - Example: `intitle:COVID-19 OR intext:coronavirus`
            - Usage: This looks for pages with the specified keyword either in their titles or in their main content.

        50. **Find Pages Similar to a Given Page:**
            - Syntax: `related:example.com`
            - Example: `related:github`
            - Usage: This finds web pages similar to the specified website.

##### Utilizing Social Media (00:32:30)

    People are always the weakest point of an organization

        Linkedin - always has photos of employees

            looking for badge photos

            Good at finding people 

            Take names and use it as name format on emailer 

            Can write a script to pull a information scraper from the website
        

        Twitter

            Gold mine for finding badges 

### Scanning and Enumeration

##### Install Kioptrix (00:38:00)

    Kioptrix - Beginner Level Vulnerable machine that you can download install and run

    https://www.vulnhub.com/entry/kioptrix-level-1-1,22/

    Refer to video for installation instructions you will need either VMware or VM Virtual Box.


#### Scanning with NMAP (47:30)

    Run Netdiscover

        netdiscover -r (IP Address)

        NMAP

            -sS used to be called stealth scanning its not as stealthy as it used to be 

        nmap -T4 -p- -A (IP Address)

            -T4 choise in speed 1-5 default has always been 4 the slower the better in terms of detection T4 is speed purpose

            -p means you want to scan all ports

            -A stands for evrything, version , operating system information, basically all information it can find on the system (-sV, -sC, )

            When scanning you can use 

            nmap -T4 -p- (IP Address)

            once the ports are found open

            nmap -T4 -p (Port numbers) -A (IP address)
 
#### Enumerating HTTPS  (1:04:00) 

##### Nikto (1:13:36)















    













    








