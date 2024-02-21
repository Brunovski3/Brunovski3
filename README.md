```Python
def personal_information():
    info = {
        "Name": "Bruno Ferreira",
        "Age": 17,
        "City": "Ribeirão Preto",
        "State": "São Paulo",
        "Country": "Brazil",
        "Interests": ["Back-end Developer", "DevOps"]
    }

    for key, value in info.items():
        if isinstance(value, list):
            value = ", ".join(value)
        print(f"{key}: {value}")


personal_information()
```
<p align="center">
   <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">
   <i class="devicon-bash-plain colored"></i>
   <img src="https://cdn.jsdelivr.net/npm/devicon@2.16.0/icons/csharp/csharp-original.svg" width="60" height="60"/>
   <img src="https://cdn.jsdelivr.net/npm/devicon@2.16.0/icons/dotnetcore/dotnetcore-original.svg" width="60" height="60"/>
   <img src="https://cdn.jsdelivr.net/npm/devicon@2.16.0/icons/javascript/javascript-original.svg" width="60" height="60"/>
   <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="60" height="60"/>
</a>
</p>
