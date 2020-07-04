# Engenharia Reversa em iOS 

### Análise Estática 

Aqui vamos ter um arquivo .zip composto pelos arquivos em geral e binários. Nesse caso, precisamos fazer a extração dos binários e desmontá-lo usando Ghidra/IDA... 

Extraia todas as informações, e comece sua análise sempre procurando por informações sensíveis presentes no código, hardcoded, PINS, chaves ou qualquer informação relevante que possa estar presente. 

Realize um bypass nos controles de segurança que possam existir, tal como SSL Pinning, detecção de Jailbreak, entre outros.  

Pegue o código decompilado, faça a modificação de lógica necessária, reconstrua o app e re-assine e instale o app. 

