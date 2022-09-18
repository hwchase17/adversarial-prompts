# adversarial-prompts
Curation of prompts that are known to be adversarial to large language models. Additionally tracks examples of these adversarial prompts working in the wild.


## Prompts
Prompts are stored in the `prompt` folder in `.txt` files. The format of the prompt should be:

```
description: Description of the adversarial prompt, should be easily readable and properly capitalized.
model: Name of the model(s) this attack works against. E.g., `text-davinci-002`. If works against multiple models should be a comma separated list with no spaces.
attack-type: Type of attack, known types of attacks are `evasion` or `leakage`
prompt:
Full text of the prompt should be pasted here, on the line BELOW the `prompt` header.
```

## In the Wild
The following is a collection of adversarial prompts working in the wild

### Evasion
[remoteli.io, 9/15/2022] (https://twitter.com/plutoniumgrist/status/1570558380045135872)

### Leakage
[remoteli.io, 9/15/2022] (https://twitter.com/mkualquiera/status/1570546998104948736)
