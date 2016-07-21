# javaLambda
javaLambda
[http://docs.oracle.com/javase/tutorial/java/javaOO/lambdaexpressions.html]

java.util.function
Interface Predicate<T>

Type Parameters: 
T - the type of the input to the predicate 
Functional Interface: 
This is a functional interface and can therefore be used as the assignment target for a lambda expression or method reference. 

--------------------------------------------------------------------------------


@FunctionalInterface
public interface Predicate<T>Represents a predicate (boolean-valued function) of one argument. 
This is a functional interface whose functional method is test(Object).

Since: 
1.8 

java.util.function
Interface Function<T,R>

Type Parameters: 
T - the type of the input to the function 
R - the type of the result of the function 
All Known Subinterfaces: 
UnaryOperator<T> 
Functional Interface: 
This is a functional interface and can therefore be used as the assignment target for a lambda expression or method reference. 

--------------------------------------------------------------------------------


@FunctionalInterface
public interface Function<T,R>Represents a function that accepts one argument and produces a result. 
This is a functional interface whose functional method is apply(Object).

Since: 
1.8 


java.util.function
Interface Consumer<T>

Type Parameters: 
T - the type of the input to the operation 
All Known Subinterfaces: 
Stream.Builder<T> 
Functional Interface: 
This is a functional interface and can therefore be used as the assignment target for a lambda expression or method reference. 

--------------------------------------------------------------------------------


@FunctionalInterface
public interface Consumer<T>Represents an operation that accepts a single input argument and returns no result. Unlike most other functional interfaces, Consumer is expected to operate via side-effects. 
This is a functional interface whose functional method is accept(Object).

Since: 
1.8 


