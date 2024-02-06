# Cooldown
Status: #InProgress 
Links: [[Systems]]
___
A cooldown is how many [[Round]]s an [[Abilities|Ability]] takes to be usable again after use. A cooldown is made of a maximum, current, and minimum which is always zero. At the start of the game, every ability is set to a "Ready" status, meaning they are ready to be used. Once used, the ability removes the "Ready" status, and starts the "Cooldown" process, where the current cooldown, starting at the maximum, counts down per round to the minimum. Once it reaches the minimum, the current is set to the maximum, and the ability is given the "Ready" status again.