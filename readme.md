# Practica 2.2 Markdown
# Games
*The last of us 2*
**God of War: Ragnarok**
`Marvel's spiderman 2`
***codigo en json***
```json
{
    "Games": [
        {
            "name": "The last of us 2",
            "Storage in GB": 76,
            "cover page": "https://static.wikia.nocookie.net/thelastofus/images/8/85/Portada_Parte_II_limpia.jpeg/revision/latest?cb=20211209014334&path-prefix=es",
            "protagonist": "Ellie",
            "antagonist": "Abby",
            "avaliable": 
            {
                "play": true,
                "PC": true,
                "swtich": false
            }
        }
        ,
        {"name": "God of War: Ragnarök",
            "Storage in GB": 84,
            "cover page": "https://img.asmedia.epimg.net/resizer/v2/EWHQBRT75JNY7CR6CQB34O7TJY.jpg?auth=fd1cf7b860f17552f35bea22b00b6e73b75ad49561920a64a14a94d6ce5dfd2d&width=644&height=362&smart=true",
            "protagonist": "Kratos",
            "antagonist": "Odin",
            "avaliable":
            {
                "play": true,
                "PC": false,
                "swtich": false
            }
        },
        {"name": "Marvel's Spiderman 2",
        "Storage in GB": 90,
        "cover page": "https://i.3djuegos.com/juegos/18168/marvel__039_s_spiderman_2/fotos/ficha/marvel__039_s_spiderman_2-5824801.webp",
        "protagonist": "Spiderman",
        "antagonist": "Kraven/Venom",
        "avaliable":
        {
            "play": true,
            "PC": false,
            "swtich": false
        }}
    ]
}
```
[friv](https://www.friv.com)
# Personajes de Dragon ball

* Goku
* Vegeta
* Gohan 
* Picolo
* Chaoz
* Trunks
* krillin

![personajes de dragon ball](https://imagenes.eltiempo.com/files/image_1200_600/uploads/2021/04/30/608c41bc6386d.jpeg)
***Codigo en yaml***
```yaml
 Games: 
          -Game 1:
            name: The last of us 2
            Storage in GB: 76
            cover page: https://static.wikia.nocookie.net/thelastofus/images/8/85/Portada_Parte_II_limpia.jpeg/revision/latest?cb=20211209014334&path-prefix=es
            protagonist: Ellie
            antagonist: Abby
            -avaliable: 
                play: true
                PC: true
                swtich: false

          -Game 2:
            name: God of War Ragnarok
            Storage in GB: 84
            cover page: https://img.asmedia.epimg.net/resizer/v2/EWHQBRT75JNY7CR6CQB34O7TJY.jpg?auth=fd1cf7b860f17552f35bea22b00b6e73b75ad49561920a64a14a94d6ce5dfd2d&width=644&height=362&smart=true
            protagonist: Kratos
            antagonist: Odin
            -avaliable:
                play: true
                PC: false
                swtich: false
                
          -Game 3:
            name: Marvel's Spiderman 2
            Storage in GB: 90
            cover page: https://i.3djuegos.com/juegos/18168/marvel__039_s_spiderman_2/fotos/ficha/marvel__039_s_spiderman_2-5824801.webp
            protagonist: Spiderman
            antagonist: Kraven/Venom
            -avaliable:
                play: true
                PC: false
                swtich: false
```
