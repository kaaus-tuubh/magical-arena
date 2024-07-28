# magical-arena
A Solution to a design problem using Java

"Magical Arena" is a Java console game where players battle using health, strength, and attack attributes. They roll dice to attack and defend, aiming to reduce opponents' health to zero. Fast-paced and strategic, it ends when a player's health depletes.


Compile the Java files using a Java compiler using command
javac Main.java
Run the game using command
java Main

Enter the attributes for Player A when prompted (health, strength, attack).
Enter the attributes for Player B when prompted (health, strength, attack).
The game will simulate the battle between the two players, with Player having less health attacking first.
The attacker's attack value, multiplied by the attacking dice roll, determines the damage inflicted, while the defender's strength value, multiplied by the defending dice roll, determines the damage defended.
Any excess damage from the attacker reduces the defender's health.
The game continues with players exchanging attacker and defender roles until one player's health reaches zero, indicating the end of the match.
The game announces the winner based on which player's health reaches zero first.
