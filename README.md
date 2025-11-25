# Assistant Virtual Personal

[![Autor: Max Muller](https://img.shields.io/badge/Autor-Max%20Muller-blue)]()
[![Python](https://img.shields.io/badge/Linguagem-Python-green)]()

## Sobre o Projeto
Este projeto implementa um assistente virtual simples em Python capaz de:
- Capturar comandos de voz via microfone.
- Reconhecer fala utilizando *SpeechRecognition* (Google API).
- Responder utilizando síntese de voz com *pyttsx3*.

É ideal para demonstrar conhecimento em processamento de áudio, integração de bibliotecas e automação por comando de voz — sendo um ótimo destaque para portfólio profissional.

## Tecnologias Utilizadas
- **Python 3.x**
- **SpeechRecognition**
- **Pyttsx3**
- **Google Speech API** (via SpeechRecognition)

## Estrutura do Código
```python
def take_commands():
    """
    Captura áudio do microfone e converte fala em texto.
    Retorna "None" em caso de erro ou reconhecimento falho.
    """
    ...

def Speak(audio):
    """
    Realiza síntese de voz a partir de texto recebido.
    """
    ...

if __name__ == '__main__':
    while True:
        command = take_commands()
        if "good morning" in command:
            Speak("Hello, good morning")
            break
```
## Como Funciona

  1. O microfone é iniciado e começa a "escutar".

  2. O áudio capturado é enviado para reconhecimento.

  3. O texto retornado é comparado com palavras-chave.

  4. Se houver correspondência, o assistente responde por voz.

## Como Executar

  Instale as dependências:

pip install pyttsx3 SpeechRecognition pyaudio

  Execute o script principal:

python assistant.py

## Possíveis Melhorias Futuras

- Adicionar integração com APIs (clima, notícias, automação residencial).

- Criar comandos personalizados.

- Utilizar modelos offline de reconhecimento de fala.

- Adicionar interface gráfica (GUI).

## Autor

Max Muller
Professor, desenvolvedor e entusiasta de soluções inteligentes.

Se este projeto ajudou você a evoluir, deixe uma ⭐ e compartilhe o conhecimento. Obrigado por usar este repositório!

![octocat-1688650978178](https://github.com/MMVonnSeek/Assistant-virtual-personal/assets/89359847/7afe39a2-31ee-4dbe-b147-7e6b14c145a0)
