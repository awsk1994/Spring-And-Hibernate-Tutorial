# 1. What are Java Annotations?

* Definition
    * Special labels/markers added to Java Classes
    * Provide meta-data about the class
    * processed at compile time or run-tiem for special processing

* Example
<img src="img/7_annotations/1.png"/>

* Why Spring configurations with Annotations?
    * XML configurations can be verbose
    * Solution: Configure your spring beans with annotations - to minimize XML configurations

* Scanning for Component Classes
    * Spring will scan your Java class for special annotations
    * Automatically register the beans in the Spring container

## 1.1 Deveopment Process

1. Enable component scanning in Spring Config file
<img src="img/7_annotations/2.png"/>

2. Add the @Component Annotation to your Java Classes
<img src="img/7_annotations/3.png"/>

3. Retrieve bean from Spring container
(same as before)
<img src="img/7_annotations/4.png"/>

2. Default Component Names

* we don't have to specify bean id, and let spring use default bean id

<img src="img/7_annotations/5.png"/>
<img src="img/7_annotations/6.png"/>

