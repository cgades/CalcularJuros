API para Calcular Juros
========================

O ASP.NET Core é uma estrutura de software livre, de multiplaforma e alto desempenho para a criação de aplicativos modernos conectados à Internet e baseados em nuvem. 
Com o ASP.NET Core, você pode:
Compilar aplicativos e serviços Web, aplicativos IoT e back-ends móveis.
Usar suas ferramentas de desenvolvimento favoritas no Windows, macOS e Linux.
Implantar na nuvem ou local.
Executar no .NET Core ou no .NET Framework.

Aqui encontrarás 2 API's: 
 - API1: http://localhost:5005/API1/taxaJuros
 - API2: http://localhost:5000/API2/calculajuros?valorinicial=999&meses=9

Como Usar ?
-----------

> A API1: traz o valor do Juros na porta 5005. utilize a chamada: API1/taxaJuros
Retorna o valor do Juros: "0,01" fixo.
	
	
> A API2 contêm 2 endpoints: API2/calculajuros
Parâmetro 1: valorinicial
Parâmetro 2: meses
Exemplo de Chamada:  http://localhost:5000/API2/calculajuros?valorinicial=100&meses=5

