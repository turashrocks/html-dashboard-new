<!-- <img src="https://raw.githubusercontent.com/turashrocks/html-dashboard-new/main/application-screenshot3.png"> -->


### hey there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">

<br />

hi, i'm [Turash C](https://ebuilders.pro/), a passionate self-taught full stack developer and a freelance software engineer. 

I am also an open-source enthusiast and maintainer. i learned a lot from the open-source community and i love how collaboration and knowledge sharing happened through open-source.
  
- 💼 any freelance work? do reach, [email](mailto:turash.chowdhury@gmail.com) :)
- 💬 ask me about anything, i am happy to help;

<h3>
    
```python
​
from __future__ import annotations

import json
from dataclasses import asdict, dataclass


@dataclass
class Arsenal:
    languages: tuple[str, ...] = ("Python", "JS", "Go")
    databases: tuple[str, ...] = ("SQLite", "PostgreSQL", "DynamoDB", "Redis")
    misc     : tuple[str, ...] = ("Docker", "Celery", "RabbitMQ", "Arq", "SQS")
    ongoing  : tuple[str, ...] = ("Django", "DRF", "Asyncio")

    def jsonify(self) -> str:
        return json.dumps(asdict(self), indent=4)


arsenal = Arsenal()
print(arsenal.jsonify())
​
```
</h3>


  <img align="right" alt="GIF" src="https://raw.githubusercontent.com/turashrocks/turashrocks/main/code.gif?raw=true" width="500" height="320" />