# Rasa-Reconhecimento-Facial
Projeto desenvolvido em rasa com reconhecimento facial

pip install -r requirements.txt

## 📌 ***Principais Objetivos***
- Fazer um chatbot utilizadno Rasa
- E reconhecimento facial utilizando python

## 🖱 ***Pré-requisitos***
- Python: 3.8.10
- Rasa: 2.7.1
- spacy: 3.2.2
- opencv-python: 4.5.5.62

## 🖥 Página Principal

 O chatbot foi desenvolvido em Rasa e utilizando Python e o principal objetivo é fazer o reconhecimento facil e de olho, conforme as imagens.

<div align=center><img src="https://github.com/GustavoMarcello/DesafioD1/blob/main/src/img/Chatbot%201%20MooVIE.png" style="width:300px;height:550px;"/>  <img src="http://3.bp.blogspot.com/-NJL-u0nj64A/VXN8nweH01I/AAAAAAAADJA/3q7gY1ggg6s/s1600/face_details.png" style="width:300px;height:550px;"/></div>


## 📚 Como utilizar
- A versão do python necessária para rodar esse projeto é a [3.8.10](https://www.python.org/downloads/release/python-388/). Verifique também a [versão do pip](https://pypi.org/project/pip/) mais atual, e se preciso, faça o upgrade com o comando abaixo.
```
pip install --upgrade pip
```
- Na raiz do projeto, execute o comando abaixo para realizar o download das bibliotecas python. 
```
pip install -r requirements.txt
```
- Para utilização do bot, será necessário o treinamento do modelo e hospedagem dos demais servidores `rasa`. Faça o download da biblioteca em português do Spacy para o treinamento.
```
spacy download pt_core_news_lg
```
- **Acesse a pasta rasa**, e treine o chatbot.
```
rasa train
```
- Ainda na pasta rasa, abra mais dois terminais para executar os servidores `core` e `action` do chatbot
```
rasa run --enable-api --cors "*"
```
```
rasa run actions
```


# 👨‍💻 ***Desenvolvedora***
- Joice Gonçalves Furigo

