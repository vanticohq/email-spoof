## E-mail Spoofing Checker

É uma ferramenta desenvolvida pela Vantico, feita toda em Python, em que sua função é basicamente verificar se certo domínio possui a verificação do DMARC e SPF ou não.

## Objetivo

O objetivo desta ferramenta é que quando a Vantico realiza o Pentest não avaliamos apenas nosso alvo, como sendo apenas a aplicação web ou o aplicativo, também avaliamos o contexto, verificamos sempre antes de realizar o Pentest, o Spoofing e buscamos comprometer de alguma forma a camada do usuário, iremos buscar outros riscos presentes no negócio.

## Requisitos
```
$ Python 3.0+
```

## Exemplo de uso
```
$ python3 spoofy.py -d (domínio)
```
![Sample screenshot](https://raw.githubusercontent.com/vanticohq/email-spoof/main/images/spoof-1.png)

![Sample screenshot](https://raw.githubusercontent.com/vanticohq/email-spoof/main/images/spoof-2.png)

## Autor

Lucas Alcantara

## Licença
This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details.
