## Spring Certification Notes
The answers on the questions are mostly based on the Spring Certification Study guide against the official documentation of Spring framework.

Spring Version `5.2.8.RELEASE`

| Referrences     | 
| ------------- |
| [Spring ProfessionalCertification Study Guide](https://pivotalcontent.s3.amazonaws.com/academy/Spring-Professional-Certification-Study-Guide.pdf)       | 
| [Spring Framework Documentation](https://docs.spring.io/spring/docs/current/spring-framework-reference/)      |


### A. Container, Dependency, and IOC

#### 1. What is dependency injection and what are the advantages?
- Also known as Inversion of Control (IoC)
- It is a process whereby objects define their dependencies (that is, the other objects they work with) only through constructor arguments, arguments to a factory method, or properties that are set on the object instance after it is constructed or returned from a factory method. The container then injects those dependencies when it creates the bean. This process is fundamentally the inverse (hence the name, Inversion of Control) of the bean itself controlling the instantiation or location of its dependencies by using direct construction of classes or a mechanism such as the Service Locator pattern.

##### Advantages
- Decoupling
- Maintainability

#### 2. What is an interface and what are the advantages of making use of them in Java?

- Why are they recommended for Spring beans?

#### 3. What is meant by 'application-context'?

#### 4. How are you going to create a new instance of an ApplicationContext?

#### 5. Can you describe the lifecycle of a Spring Bean in an ApplicationContext?

#### 6. How are you going to create an ApplicationContextin an integration test?

#### 7. What is the preferred way to close an application context Does Spring Boot do this for you?