Lab Exercise Tasks
    Task 1: Analyze the Code
      Objective: Review the provided code and identify where it violates any of the SOLID principles. Consider aspects like class responsibilities, method functionalities, dependency management, and object substitution.
Principios que fueron violados
Principio abierto/cerrado (OCP): ya que debe de estar abiertas para la extensión, pero cerradas para la modificaciones de lo existente.
Principio de inversión de dependencia (DIP): módulos de alto nivel no deben depender de módulos de bajo nivel, sino de abstracciones.
Principio de responsabilidad única (SRP): Solo debe tener un solo trabajo. lleva a menos complicaciones.
<img width="767" alt="Captura de pantalla 2024-05-15 a la(s) 8 48 52 p m" src="https://github.com/KarlaPR10/Lab2/assets/138635602/c983d7aa-91b6-48ce-b666-ca22c2cfb83a">
    Task 2: Refactor the Code
        Objective: Modify the code to address the identified violations. Ensure each component or class adheres more closely to the SOLID principles. Aim to enhance the system’s overall design in terms of scalability, flexibility, and maintainability.
<img width="615" alt="Captura de pantalla 2024-05-15 a la(s) 8 56 17 p m" src="https://github.com/KarlaPR10/Lab2/assets/138635602/05f25ecd-7c06-44f9-a17e-dfc76318d72c">
<img width="680" alt="Captura de pantalla 2024-05-15 a la(s) 8 56 26 p m" src="https://github.com/KarlaPR10/Lab2/assets/138635602/68369229-9a1c-4e90-a3b6-ec0b73605e74">
    Task 3: Document Your Changes
        Objective: For each modification you make, provide a detailed explanation of:
What the issue was.
Which SOLID principle it violated.
How your change addresses this violation.
The benefits your changes bring to the system’s architecture.
Principios violados se tocan en el task 1.
Se realizaron los siguientes ajuste para no violar los principios de SOLID
Se agrego Single Responsibility Principle para cumplier con la responsabilidad de que solo se tuviera que hacer un solo trabajo, Open/Closed Principle para que estuviera  abierto para posibles desarrollos nuevos pero a su vez cerrado para la modificación, Dependency Inversion Principle para que los módulos de alto nivel no dependadn de de módulos de bajo nivel, sino de abstracciones y Interface Segregation Principle  se ajusto para que use interfaces y sea mas facirl de entender el codigo. 
El beneficio que llevarias seria tener un codigo mas legible e intentar respetar los principios de SOLID







