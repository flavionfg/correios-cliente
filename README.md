# correios-cliente
Consumindo o serviço dos Correios

Acesse esse endereço e clique no link para fazer o download da especificação do serviço. O WSDL do serviço se encontra aqui:

http://ws.correios.com.br/calculador/CalcPrecoPrazo.asmx?WSDL

rodar o comando no diretório do projeto:

wsimport -s src/ -p br.com.caelum.correios.soap http://ws.correios.com.br/calculador/CalcPrecoPrazo.asmx?WSDL

rodar a classe TesteClienteCorreios.
