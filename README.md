# Teste-Python
Teste com Django

Teste: Diego de Souza

http://127.0.0.1:8000/admin/
http://127.0.0.1:8000/teste/


TELAS:

* Cadastro de cidades
* Listagem das cidades cadastradas
* Pesquisar as cidades registradas no arquivo json 
* Detalhar as previsões do tempo com forecast de 5 dias

* Utilizado Python 3.7 e Djando 2.4
* Banco de Dados utilizado db.sqlite3 (Vem como padrão no Djando)

Criado no virtualenv

Link da CONSULTA:

Utilizar o Link disponibilizado passando dois parâmetros (Id da Cidade e Chave da Api)
https://samples.openweathermap.org/data/2.5/forecast?id={Id da Cidade}appid={Chave da Api}

Exemplo, Teste feito para a cidade de Blumenau com o API key disponibilizado pelo Teste:

Cidade de Blumenau, ID = 6323074
API key = eb8b1a9405e659b2ffc78f0a520b1a46

https://samples.openweathermap.org/data/2.5/forecast?id=6323074&appid=eb8b1a9405e659b2ffc78f0a520b1a46


IDENTIFICAR as cidades:

Todas as cidades estão registradas no arquivo "city.list.json".
Realizar a consulta do Id da cidade através desse arquivo, passando o nome da cidade e o código ISO do País.

Exemplo:
Cidade = Blumenau
Código ISO do país = BRA

Retorno = 
{
   "id": 6323074,
   "name": "Blumenau",
   "country": "BR",
   "coord": {
	  "lon": -49.102268,
	  "lat": -26.87417
   }
}





