---

# Projeto de Otimização de Recursos e Distribuição de Sensores no Ambiente Marinho
 
Este projeto consiste em um conjunto de ferramentas e algoritmos para otimizar a alocação de recursos e distribuir sensores de forma eficiente no ambiente marinho. O objetivo principal é ajudar na conservação e monitoramento dos ecossistemas marinhos, permitindo uma melhor gestão de recursos e uma cobertura mais eficaz das áreas de interesse.
 
## Funcionalidades
 
O projeto inclui as seguintes funcionalidades:
 
1. **Otimização da Alocação de Recursos:**
   - Algoritmos de programação dinâmica para selecionar projetos e maximizar o lucro total, considerando restrições de recursos disponíveis.
 
2. **Distribuição Ótima de Sensores:**
   - Métodos para distribuir sensores de poluição oceânica de forma a minimizar a distância total entre os sensores, garantindo uma cobertura eficiente da área de monitoramento.
 
3. **Cálculo do Valor de Áreas Marinhas:**
   - Funções para calcular o valor de uma área marinha com base em critérios como biodiversidade, vulnerabilidade e conectividade.
 
4. **Distribuição Uniforme de Sensores:**
   - Algoritmo para distribuir sensores de forma uniforme em uma área retangular, facilitando a implantação de uma rede de monitoramento.
 
## Instruções de Uso
 
1. **Instalação das Dependências:**
   - Certifique-se de ter as dependências necessárias instaladas. Você pode instalá-las usando pip:
     ```
     pip install numpy
     ```
 
2. **Execução do Código:**
   - Execute os scripts Python fornecidos para acessar as funcionalidades do projeto. Cada script contém exemplos de uso para demonstrar como utilizar as funções.
 
3. **Personalização e Integração:**
   - Sinta-se à vontade para personalizar os algoritmos e funções de acordo com suas necessidades específicas. Você também pode integrar essas funcionalidades em seus próprios projetos.
 
## Exemplos de Uso
 
Aqui estão alguns exemplos de uso das funcionalidades do projeto:
 
```python
# Exemplo de otimização da alocação de recursos
lucro_maximo, projetos_selecionados = otimizar_alocacao_recursos(projetos, recursos_disponiveis)
print("Lucro máximo:", lucro_maximo)
print("Projetos selecionados:")
for lucro, recursos_necessarios in projetos_selecionados:
    print(f"Projeto com lucro {lucro} e requer {recursos_necessarios} unidades de recursos.")
 
# Exemplo de distribuição ótima de sensores
distribuicao_otima = encontrar_distribuicao_otima_sensores(area_monitoramento, sensores_disponiveis)
print("Distribuição ótima dos sensores:")
print(distribuicao_otima)
```

## Bibliografia

**Bang, H., Lee, S. K., Kim, H., & Park, H. (2015). *A review on optimal sensor placement for water distribution networks.* Journal of Hydroinformatics, 17(4), 491-503.**
- Este artigo revisa as estratégias e métodos para o posicionamento ótimo de sensores em redes de distribuição de água. Ele aborda desafios específicos relacionados à monitorização de sistemas de abastecimento de água, como detecção de vazamentos, qualidade da água e eficiência operacional, e discute abordagens de otimização para melhorar o desempenho desses sistemas.
 
**Clark, J. S. (2016). *Dynamic programming and optimal control.* CRC Press.**
- Este livro é uma excelente fonte para entender os princípios fundamentais da programação dinâmica e controle ótimo. Ele aborda conceitos-chave, como a formulação de problemas de otimização, o princípio do princípio da otimalidade de Bellman, algoritmos de programação dinâmica, e sua aplicação em uma variedade de áreas, incluindo engenharia, economia e ciências ambientais.

# Anny Dias RM:98295 e Luana Cabezaolias RM:99320
---
 
 
