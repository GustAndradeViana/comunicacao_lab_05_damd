**Você chamou proxy.calcular("soma", 10, 3) como se fosse uma função local. Onde, exatamente, ocorre a serialização XML? Inspecione o tráfego HTTP com logRequests=True no servidor e observe o que é transmitido.**


**O que é um xmlrpc.client.Fault? Como ele se compara a uma exceção Python convencional? Por que o RPC precisa de um mecanismo especial para propagar erros do servidor para o cliente?**


**O método system.listMethods() demonstra introspecção remota. Qual das transparências da ISO/RM-ODP (vistas no Lab 04) esse recurso relaciona-se mais diretamente? Justifique.**


**Identifique no código as quatro etapas do ciclo de uma chamada RPC descritas por Birrell & Nelson (1984): marshalling, transmissão, dispatching e unmarshalling. Em qual linha de código cada etapa ocorre?**


**O XML-RPC usa XML; o gRPC usa Protobuf binário; este stub usa JSON. Qual a consequência prática de usar JSON em vez de Protobuf para um sistema com alto volume de chamadas? Considere tamanho de payload e overhead de parsing.**


**O framing (4 bytes de tamanho + payload) é necessário por uma propriedade do protocolo TCP. Qual é essa propriedade, e o que aconteceria se você não usasse framing?**


