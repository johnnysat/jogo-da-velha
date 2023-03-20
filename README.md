# Jogo da Velha 
O projeto acompanha as aulas do MacroBrunoDev que compartilhou o conteúdo do seu curso de forma gratuída no Youtube. A proposta é acompanhar o vídeo para aplicar o conhecimento enquanto entende as explicações e executo exercícios junto com o professor. 

## Arquitetura de Pastas - ITCSS
A arquiteura de pastas ITCSS utiliza como passe o Styled-Comoponents do React. Agindo como uma pirâmide invertida entre pastas, é normal que os arquivos sejam utilizados através das pastas pelo consumo de recursos internos. Uma pasta pode consumir recursos de uma pasta acima, mas não de uma pasta abaixo. 

### Organização de Pastas
- Settings (variaveis)
- Tools (funções)
- Generic (reset.css)
- Base/Elements(Definição de elementos e bases)
- Objects (Criação de Elementos e Components Genéricos)
- Components (Relacionado a components mais específicos e poucos genéricos)