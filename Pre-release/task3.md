Task3

3.1

character(bob). character(David). character(habib). character(Michael). 
character_type(bob,prince). character_type(David,princess). character_type(habib,explorer). character_type(Michael,king). 
3.2

has_skill(X,Y):- character(X), skill(Y).

haspet(X,Y):- character(X), animal(Y).

3.3
hasskill(bob,fly). 
hasskill(David,invisibility). 
hasskill(habib,timetravel). 
hasskill(Michael,sing). 
pet(Bob,horse). pet(David,bird). 
pet(habib,fish). 
pet(Michael,dog). 
animal(horse). 
animal(bird). 
animal(fish). 
animal(dog). 
skill(fly). 
skill(invisibility). 
skill(timetravel). 
skill(sing).
task 3.4

True pricess Bob invisibility Bob

task 3.5

pet(jim,X). has_skill(X,fly). skill(X). pet(X,Y),character_type(X,princess).