# Music Bot Icons 🎵

Un ensemble d'icônes destinées à être utilisées pour des bots Discord musicaux.  
Ces icônes peuvent bien sûr être utilisées dans d'autres projets si besoin.

## Contenu

| Icône      | Usage principal             |
|-----------|----------------------------|
| <img src="/pause.png" alt="pause">   | Bouton pause               |
| <img src="/play.png" alt="play">  | Bouton reprendre           |
| <img src="/stop.png" alt="stop">    | Bouton stop                |
| <img src="/expand.png" alt="expand">  | Bouton pour afficher complet |
| <img src="/collapse.png" alt="collapse"> | Bouton pour réduire l'affichage |
| <img src="/youtube.png" alt="youtube"> | Bouton pour accéder à la musique sur YouTube |
| <img src="/spotify.png" alt="spotify"> |  Bouton pour accéder à la musique sur Spotify |
| <img src="/soundcloud.png" alt="soundcloud"> |  Bouton pour accéder à la musique sur SoundCloud |

## Utilisation dans un bot Discord

Vous pouvez utiliser ces icônes dans vos boutons Discord avec `discord.PartialEmoji` :

```python
pause_btn = discord.ui.Button(
    style=discord.ButtonStyle.secondary,
    emoji=discord.PartialEmoji(
        name="pause",
        url="https://raw.githubusercontent.com/StarKev/music-bot-icons/main/pause.png"
    )
)
```

## Auteur  

| [![Star Kev](https://github.com/StarKev.png?size=100)](https://github.com/StarKev) |
| ---------------------------------------------------------------------------------------- |
| [Star Kev](https://github.com/StarKev)                                               |  

## Licence  

```text
Copyright (C) 2023-2025 StarKev

Licensed under the CC BY-NC-SA 4.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://creativecommons.org/licenses/by-nc-sa/4.0/

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
