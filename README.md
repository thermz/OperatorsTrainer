# OperatorsTrainer

Java Operators Trainer is an excellent tool that could be useful for anyone who wants to get one of the Oracle IZ0-*** java certification, or for anyone who just want to learn more about Java operators and their precedence order.

It might be confusing when a java expression contains many operators with no parentheses:

```
var x = 4;
double i = (int) 5.7 / 3 - x ++ + (x >>= x ^ 6) + 'a' ;
```

For as bad as it may seems, this code compiles! Remembering the precedence order of operators in Java is a bit of a challenge, but many questions in OCP tests actually requires this kind of knowledge, and remembering all the operators precedence table rows is not easy as it seems.

This tool helps you training with this specific and tricky aspect of Java. Just download the latest jar version at https://github.com/thermz/OperatorsTrainer/blob/master/target/OperatorsTrainer-1.0.jar and then execute it!

Click the **Start** button and choose for each couple of randomly chosen operators which one has more precedence or choose if both have the same precedence.
Click the **Stop** button to complete the challenge when you're done, and check your score result %, based on how many correct answers you provided.

If you score above 90% with at least 30 attempts it means you're really good and you probably are ready to try many OCP exam questions about operators precedence with a good confidence.

If you have any suggestion or amy idea for improvement feel free to fork the project and send me a pull request.

![Alt text](OperatorsTrainer.PNG?raw=true "Example")
![Alt text](OperatorsTrainer_End.PNG?raw=true "Example")

*The Java swing application has been coded with Netbeans IDE support and build with maven.
No external java dependency is necessary for this program to run.*
