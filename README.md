## WEEK 1 — Core Java Foundations

### Day 1
- [ ] Udemy: Java setup, variables, data types, operators (45 min)
- [ ] Write 5 programs: swap two numbers, check even/odd, simple calculator, temperature converter, area of shapes
- [ ] No copy-paste — retype everything from scratch after watching

### Day 2
- [ ] Udemy: Control flow — if/else, switch, loops (45 min)
- [ ] Write: FizzBuzz, print multiplication table, check prime number, reverse a number, count digits
- [ ] Solve 2 HackerRank "Java" easy problems on loops

### Day 3
- [ ] Udemy: Classes, objects, constructors, `this` keyword (1 hr)
- [ ] Build a `Student` class: fields (name, roll, marks), constructor, a method to print details
- [ ] Build a second class `Employee` on your own, no video, using what you just learned

### Day 4
- [ ] Udemy: Static vs instance members, method overloading (45 min)
- [ ] Add overloaded constructors to your `Student` class (with/without marks)
- [ ] Write a `MathUtils` class with 3 overloaded `add()` methods (int, double, three ints)

### Day 5
- [ ] Udemy: Inheritance — extends, super keyword (1 hr)
- [ ] Build: `Animal` → `Dog`, `Cat` subclasses, override a `sound()` method
- [ ] Write down in your own words: difference between overloading and overriding (you'll be asked this)

### Day 6
- [ ] Udemy: Abstraction — abstract classes vs interfaces (1 hr)
- [ ] Build: `Shape` abstract class with abstract `area()` → `Circle`, `Rectangle` implement it
- [ ] Rebuild the same thing using an interface instead of abstract class — compare mentally when you'd use which

### Day 7
- [ ] Udemy: Exception handling — try/catch/finally, checked vs unchecked (1 hr)
- [ ] Write a program with 3 custom exceptions (e.g., `InvalidAgeException`, `InsufficientBalanceException`)
- [ ] **Review**: Explain OOP (all 4 pillars) out loud, no notes. If you stumble, redo that topic tomorrow morning before moving on.

---

## WEEK 2 — Collections, Strings, Multithreading, Practice

### Day 8
- [ ] Udemy: ArrayList, LinkedList (45 min)
- [ ] Write programs: store 10 student names in ArrayList, sort them, remove duplicates
- [ ] Know: when to use ArrayList vs LinkedList (interview question)

### Day 9
- [ ] Udemy: HashMap, HashSet, Iterator (1 hr)
- [ ] Write: word frequency counter using HashMap, find duplicate elements in array using HashSet
- [ ] Know: why HashMap lookup is O(1) — be able to explain simply

### Day 10
- [ ] Udemy: String handling — immutability, StringBuilder vs StringBuffer (45 min)
- [ ] Write: reverse a string (without built-in reverse), check palindrome, count vowels/consonants, remove duplicate characters
- [ ] Solve 3 string problems on HackerRank/LeetCode easy

### Day 11
- [ ] Udemy: Multithreading basics — Thread class, Runnable, synchronized (1 hr)
- [ ] Write a basic program creating 2 threads printing numbers simultaneously
- [ ] Just get comfortable explaining it — don't over-invest time here

### Day 12
- [ ] Solve 8-10 LeetCode/HackerRank easy problems (arrays + strings), timed, no googling mid-attempt
- [ ] Review any problem you couldn't solve — rewrite the solution yourself after seeing the approach

### Day 13
- [ ] Solve 8-10 more problems, mix of arrays, strings, basic OOP design questions
- [ ] Time yourself — aim for 15-20 min per easy problem

### Day 14 — Review Day
- [ ] Explain out loud (to yourself, a friend, or record yourself): OOP pillars, exception handling, collections differences, string immutability
- [ ] If you can't explain any topic clearly in 2 minutes, redo it — don't move to Week 3 with gaps

---

## WEEK 3 — SQL, JDBC, Project 1

### Day 15
- [ ] Udemy/SQLZoo: SELECT, WHERE, ORDER BY, LIMIT (1 hr)
- [ ] Practice 10 queries on a sample database (SQLZoo or free dataset)

### Day 16
- [ ] Udemy: JOINs (inner, left, right), GROUP BY, subqueries (1 hr)
- [ ] Practice 10 more queries specifically using joins — this gets tested constantly

### Day 17
- [ ] Install MySQL + Workbench locally
- [ ] Create a database, 2-3 tables (students, courses, enrollments) manually with proper keys

### Day 18
- [ ] Insert, update, delete data manually via SQL
- [ ] Practice writing queries that join your own tables

### Day 19
- [ ] Udemy: JDBC — Connection, Statement, ResultSet (1 hr)
- [ ] Write a Java program that connects to MySQL and reads data from your table, prints it to console

### Day 20
- [ ] Extend JDBC program: full CRUD (insert, update, delete, read) from Java, no framework yet
- [ ] Debug any connection errors yourself before searching — builds real troubleshooting skill

### Day 21 — Project 1
- [ ] Build: Console-based Student/Inventory Management System using JDBC + MySQL
- [ ] Must support: add record, view all, update record, delete record — menu-driven
- [ ] Push to GitHub with a basic README (what it does, how to run it)

---

## WEEK 4 — Spring Boot, Project 2, Git, Wrap-up

### Day 22
- [ ] Udemy (in28Minutes or Amigoscode): Spring Boot intro, project setup via Spring Initializr (1 hr)
- [ ] Understand: what dependency injection is, @Component, @Service, @Repository — write it in your own words

### Day 23
- [ ] Udemy: @RestController, @RequestMapping, GET/POST endpoints (1 hr)
- [ ] Build a simple "Hello World" REST API, test it with Postman

### Day 24
- [ ] Udemy: Spring Data JPA — @Entity, @Repository interface, connecting to MySQL (1 hr)
- [ ] Rebuild your Project 1 database connection using Spring Data JPA instead of raw JDBC

### Day 25
- [ ] Build full CRUD REST endpoints (GET, POST, PUT, DELETE) for one entity (e.g., Book or Employee)
- [ ] Test every endpoint in Postman, note down request/response examples

### Day 26 — Project 2 (Day 1)
- [ ] Design and start: Book Library or Employee Management REST API
- [ ] Entities, repository, service layer, controller layer — structure it properly (don't dump everything in one file)

### Day 27 — Project 2 (Day 2)
- [ ] Finish all CRUD endpoints
- [ ] Add basic validation (e.g., no empty names, no negative salaries)
- [ ] Full Postman test pass — screenshot or save example requests

### Day 28 — GitHub Cleanup
- [ ] Push Project 2 to GitHub
- [ ] Write proper README for both projects: tech stack, features, how to run, sample API calls
- [ ] Clean up commit history if it's messy (optional but good practice)

### Day 29 — Git Practice
- [ ] Practice: branch creation, making changes, merging, resolving a deliberate merge conflict
- [ ] Practice `git log`, `git diff`, `git stash` — small things freshers fumble in interviews

### Day 30 — Mock Self-Interview
- [ ] Walk through both projects' code out loud, unscripted, as if explaining to an interviewer
- [ ] Explain: your SQL joins, your OOP design choices, why Spring Boot annotations are where they are
- [ ] Note down 3 things you're still shaky on — keep practicing those in your actual training period

---

## Daily Non-Negotiables (all 30 days)
- Minimum 1.5–2 hours hands-on coding
- Type every example yourself, never copy-paste
- Keep a running notes doc of confusing concepts, revisit weekly
- Don't skip project days even if behind on concepts — projects are your actual proof of skill
