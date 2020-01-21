
Kotlin is immensely practical. It addresses the problems that developers have, and not some guys in the academia. 
So, it has type inference, it has amazing type safety, good collection library, and concurrency library to top it. 
And it's now official - a lot of organisations are migrating their backend applications to Kotlin, 
and this trend is not likely to end soon. Follow along to check the most complete and comprehensive collection 
of the most common and advanced Kotlin Interview Questions every Android developer should know in 2020. 

> You could also find all the answers here 👉 https://www.fullstack.cafe/Kotlin.

### Q1: How to initialize an array in Kotlin with values? ⭐⭐

**Questions Details:**

In Java an array can be initialized such as:

```java
 int numbers[] = new int[] {10, 20, 30, 40, 50}
```

How does Kotlin's array initialization look like?


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q2: How to correctly concatenate a String in Kotlin? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q3: What is basic difference between fold and reduce in Kotlin? When to use which? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q4: What is the idiomatic way to remove duplicate strings from array? ⭐⭐

**Questions Details:**

How to remove duplicates from an `Array<String?>` in Kotlin?


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q5: What is the difference between var and val in Kotlin? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q6: Where should I use var and where val? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q7: What is a data class in Kotlin? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q8: What is a primary constructor in Kotlin? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q9: How to create singleton in Kotlin? ⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q10: What will be result of the following code execution? ⭐⭐⭐

**Questions Details:**

What will be the output?
```kotlin
val aVar by lazy {
    println("I am computing this value")
    "Hola"
}
fun main(args: Array<String>) {
    println(aVar)
    println(aVar)
}
```


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q11: Explain lazy initialization in Kotlin ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q12: Explain the Null safety in Kotlin ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q13: Explain what is wrong with that code? ⭐⭐⭐

**Questions Details:**

Why is this code wrong?

```kotlin
class Student (var name: String) {
    init() {
        println("Student has got a name as $name")
    }

    constructor(sectionName: String, var id: Int) this(sectionName) {
    }
}
```


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q14: How are extensions resolved in Kotlin and what doest it mean? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q15: What is a purpose of Companion Objects in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q16: What is Lateinit in Kotlin and when would you use it? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q17: When to use lateinit over lazy initialization in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q18: May you briefly compare Kotlin vs Java? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q19: What are coroutines in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q20: What is the difference between suspending vs. blocking? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q21: What is suspending function in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q22: What is the equivalent of Java static methods in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q23: Explain advantages of "when" vs "switch" in Kotlin ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q24: What are the advantages of Kotlin over Java? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q25: What are some disadvantages of Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q26: What is the difference between "open" and "public" in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q27: What is the difference between “const” and “val”? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q28: How to convert List to Map in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q29: val mutableList vs var immutableList. When to use which in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q30: What is the difference between List and Array types? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q31: What is the idiomatic way to deal with nullable values, referencing or converting them? ⭐⭐⭐

**Questions Details:**

If I have a nullable type `Xyz?`, I want to reference it or convert it to a non-nullable type `Xyz`. What is the idiomatic way of doing so in Kotlin?


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q32: When would you use Elvis operator in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q33: Rewrite this code in Kotlin ⭐⭐⭐

**Questions Details:**

Can you rewrite this Java code in Kotlin?
```java
public class Singleton {
    private static Singleton instance = null;
    private Singleton(){
    }
    private synchronized static void createInstance() {
        if (instance == null) {
            instance = new Singleton();
        }
    }
    public static Singleton getInstance() {
        if (instance == null) createInstance();
        return instance;
    }

```


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q34: What is a difference between a class and object in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q35: How is it recommended to create constants in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q36: May you use IntArray and an Array<Int> is in Kotlin interchangeably? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q37: How would you create a singleton with parameter in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q38: What is the Kotlin double-bang (!!) operator? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q39: What is the purpose of Unit-returning in functions? Why is VALUE there? What is this VALUE? ⭐⭐⭐

**Questions Details:**

Explain what is the purpose of Unit-returning in functions? Why is VALUE there? What is this VALUE?
```kotlin
fun printHello(name : String?) : Unit { 
   if (name != null) 
     print("Hello, $name!") 
   else 
     print("Hi there!") 
   // We don't need to write 'return Unit.VALUE' or 'return', although we could 
}
```


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q40: What are scope functions in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q41: Why would you use apply in Kotlin? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q42: How would you refactor this code using "apply"? ⭐⭐⭐

**Questions Details:**

Consider:
```kotlin
class Message(message: String, signature: String) {
  val body = MessageBody()
  
  init {
    body.text = message + "\n" + signature
  }
}
```
Do you see any refactoring that could be done?


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q43: Why is there no static keyword in Kotlin? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q44: What is inline class in Kotlin and when do we need one? Provide an example. ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q45: Provide a real use case when inline classes may be useful ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q46: What is Coroutine Scope and how is that different from Coroutine Context? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q47: Explain the difference between Inline classes vs type aliases ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q48: How would you override default getter for Kotlin data class? ⭐⭐⭐⭐

**Questions Details:**

Given the following Kotlin class:
```kotlin
data class Test(val value: Int)
```
How would I override the Int getter so that it returns `0` if the value negative?


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q49: How can I create “static” method for enum in Kotiln? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q50: How to create an instance of anonymous class of abstract class in Kotlin? ⭐⭐⭐⭐

**Questions Details:**

Assume that `KeyAdapter` is an abstract class with several methods that can be overridden.

In java I can do:
```kotlin
KeyListener keyListener = new KeyAdapter() {
    @Override public void keyPressed(KeyEvent keyEvent) {
        // ...
    }
};
```
How to do the same in Kotlin?


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q51: How to create empty constructor for data class in Kotlin? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q52: What are Object expressions in Kotlin and when to use them? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q53: What is Kotlin backing field is used for? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q54: Rewrite this code using "run" extension function  ⭐⭐⭐⭐

**Questions Details:**

Consider:
```kotlin
val generator = PasswordGenerator()
generator.seed = "someString"
generator.hash = {s -> someHash(s)}
generator.hashRepititions = 1000

val password: Password = generator.generate()
```
How would you refactor this code using `run` extension function?


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q55: Explain the difference between lateinit and lazy in details ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q56: What's wrong with that code? ⭐⭐⭐⭐⭐

**Questions Details:**

Let's say I want to override the Int getter so that it returns 0 if the value negative for the data class. What's bad with that approach?

```kotlin
data class Test(private val _value: Int) {
  val value: Int
    get() = if (_value < 0) 0 else _value
}
```


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q57: What is SAM Conversion in Kotlin? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q58: What is the difference between “*” and “Any” in Kotlin generics? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q59: Why do we use “companion object” as a kind of replacement for Java static fields in Kotlin? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q60: Imagine you moving your code from Java to Kotlin. How would you rewrite this code in Kotlin? ⭐⭐⭐⭐⭐

**Questions Details:**

```java
public class Foo {
    private static final Logger LOG = LoggerFactory.getLogger(Foo.class);
}
```


 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q61: How Kotlin coroutines are better than RxKotlin/RxJava? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q62: What is the difference between launch/join and async/await in Kotlin coroutines? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q63: What is a motivation to make classes final by default in Kotlin? Do you agree with that decision? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q64: How does the reified keyword in Kotlin work? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q65: What is The Billion Dollar Mistake? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q66: What is the difference between Java field and Kotlin property? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q67: How to implement Builder pattern in Kotlin? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**


### Q68: When to use and do not use an inline function in Kotlin? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Kotlin)**

















