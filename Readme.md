Mortal Combat Game

tech stack involved:
 - Django 
 - Channels 
 - RabbitQM
 - Postgresql
 - Docker
 
- User 
    * username
    * password
    * heroes_list

    - Register
    - Login
    - select_hero()
    - get_heroes_availables()
    - get_my_heroes()
    - start_combat
    - get_history()

- Heroe 
    * Level     int 
    * Salud     int
    * Strength    int
    * Agilidad  int 
    * Attack_moves     [{},] list of dicts
    * Defense_moves     [{}]
    - damage() = attack_base + 0.07*Strength
    - agilidad() = Probability_avoid + 0.08*Agilidad%
