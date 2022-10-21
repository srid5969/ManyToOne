# OneToManyAndManyToOne




In the object-relational model, the One-To-Many relationship refers to One parent entity that has a correspondence to zero or more child entities. A simple real-world example of this would be between a Branch of a Bank and the Accounts in that branch.





You might see a similar explanation on our Many-To-One relationship using JPA. But you have to understand that the One To Many relationship is nothing but the reverse of Many To One relationship mapping.




Using @OneToMany Annotation in Spring JPA
The @OneToMany annotation is from the java persistence API specification. This annotation represents that a collection of objects are direct children of the current entity. So let us see how this annotation works. For this, We are going to use the same entities from our previous @ManyToOne example.

But with a little twist, we are going to add @OneToMany mapping at the Branch entity.
