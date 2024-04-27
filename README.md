# extractMetricEvolution
 
Como extrair as métricas evolutivas:

1.clone o repositório extractMetricEvolution</br>
2.crie uma pasta com o nome projectA</br>
3.crie uma pasta com o nome projectB</br>
4.em cada pasta project clone o projeto a ser extraído as métricas. Para isso utilizar o comando</br>
    git clone url do repositorio.</br>
5.execute o arquivo main do repositório extractMetricEvolution.</br>
    Exemplo de execução do main:</br>
        python main.py --pathA 'C:\Users\usuario\Desktop\projectA\nomeDoProjeto' --pathB 'C:\Users\usuario\Desktop\projectA\nomeDoProjeto' --commits 'csv' --projectName 'nomeDoProjeto' --absolutePath 'C:\Users\usuario\Desktop\' --mode 'tag'
