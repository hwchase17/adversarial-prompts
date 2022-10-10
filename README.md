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

* [remoteli.io's Twitter bot](https://arstechnica.com/information-technology/2022/09/twitter-pranksters-derail-gpt-3-bot-with-newly-discovered-prompt-injection-hack/)
* [Google's LaMDA off topic](https://simonwillison.net/2022/Sep/18/michelle-m/)


## Defenses
The following is a collection of proposed defenses

* [k-shot prompt for non-instruct model, or create your own finetune](https://twitter.com/goodside/status/1578278974526222336?s=20&t=3UMZB7ntYhwAk3QLpKMAbw)
	* Update: [evasion against k-shot prompt](https://twitter.com/povgoggles/status/1578289474530086918?s=20&t=3UMZB7ntYhwAk3QLpKMAbw)
