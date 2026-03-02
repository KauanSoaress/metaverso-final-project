# Zoológico Virtual VR

## Sobre o Projeto

O projeto se trata de um zoológico em realidade virtual, onde os usuários podem explorar e visualizar os animais que habitam nele de forma imersiva. O objetivo é criar uma experiência interativa e educativa para os visitantes através da tecnologia VR.

Inicialmente, a ideia era um zoológico contendo animais já extintos, mas devido à dificuldade de achar os modelos 3D necessários, houve uma mesclagem entre animais extintos e atuais, o que resultou em um zoológico mais diversificado e interessante.

## Tecnologias Utilizadas

- **Unity** - Game Engine para desenvolvimento
- **OpenXR** - Framework multiplataforma para realidade virtual
- **Meta XR SDK** - SDK para desenvolvimento de experiências Meta Quest


## Requisitos do Sistema

### Para Desenvolvimento:
- Unity 2021.3 LTS ou superior
- Meta XR SDK instalado via Unity Package Manager
- OpenXR Plugin

### Para Execução:
- Headset VR compatível com OpenXR
- Controladores VR
- Espaço adequado para movimentação
- Meta XR Simulator (para testes sem headset, embora tenha apresentado dificuldades)

## Como Executar

1. Clone o repositório
2. Abra o projeto no Unity
3. Certifique-se de que todas as dependências estão instaladas (OpenXR, Meta XR SDK)
4. Conecte seu headset VR
5. Execute via Unity Editor ou faça o build para sua plataforma

## Dificuldades Encontradas

### Modelos 3D
- Falta de modelos 3D de animais extintos disponíveis, o que limitou a variedade de espécies que poderiam ser incluídas no zoológico virtual
- Necessidade de adaptar o conceito original para incluir animais atuais

### Meta XR Simulator
- Dificuldade principal foi o uso do Meta XR Simulator, que foi impossível no contexto de desenvolvimento
- Isso impediu a realização de testes da aplicação em ambiente de realidade virtual sem headset
- Foram realizados diversos testes em diferentes projetos, além de inúmeras buscas na internet e contato com monitores
- Nenhuma solução definitiva foi encontrada para o problema do simulador

## Funcionalidades

- Exploração livre do ambiente do zoológico
- Visualização de animais em seus habitats

## Autor

**Kauan Soares**