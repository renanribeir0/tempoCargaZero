## Descrição do Teste
Este teste tem como objetivo avaliar o desempenho de uma página da web em uma situação de carga zero, ou seja, quando nenhum tráfego ou solicitação concorrente está ocorrendo no sistema. O objetivo é medir o tempo de resposta da página em condições ideais.

## Pré-condição
![image](https://github.com/renanribeir0/tempoCargaZero/assets/110369271/ba2c003f-1fef-4224-a234-ae8f6458f4bc)

- O sistema está em um estado limpo, sem tráfego ou solicitações anteriores.
- O servidor da página da web está em execução.

## Procedimento de Teste
1. Abra o Postman.
2. Crie uma nova coleção de testes chamada "Carga Zero - Página da Web".
3. Dentro da coleção, crie uma nova solicitação chamada "Teste de Carga Zero".
4. Configure a solicitação para acessar a URL da página da web que será testada.
   - **Método HTTP:** GET
   - **URL:** [http://localhost:3001/iniciativas]
5. Execute a solicitação.
6. Registre o tempo de resposta da solicitação.

## Pós-condição
- A solicitação é executada com sucesso.
- O tempo de resposta da solicitação é registrado.

## Resultados Esperados
Espera-se que a solicitação seja concluída com sucesso e que o tempo de resposta seja de 1 a 2 segundos, uma vez que não há carga no sistema.

## Resultados Obtidos
![image](https://github.com/renanribeir0/tempoCargaZero/assets/110369271/9e2f74c1-6869-42d6-bfd2-915e67d3bff6)

Após a execução do teste, os resultados foram os seguintes:
- A solicitação foi concluída com sucesso.
- O tempo de resposta da solicitação foi de aproximadamente 1434.82 ms, confirmando que a página da web responde rapidamente em uma situação de carga zero.



