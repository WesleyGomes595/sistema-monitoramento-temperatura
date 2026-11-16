# Sistema de Monitoramento e Controle de Temperatura

Simulador interativo de um sistema lógico de monitoramento e controle de temperatura para refrigeração comercial, desenvolvido com HTML, CSS e JavaScript.

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte da disciplina de **Eletrônica Digital e Analógica**, com o objetivo de demonstrar a aplicação dos conceitos de lógica digital em um sistema de monitoramento de um refrigerador comercial.

O simulador permite alterar as condições de funcionamento do equipamento e visualizar, em tempo real, como essas alterações interferem nas saídas do circuito lógico.

## ⚙️ Funcionamento do sistema

O sistema utiliza três entradas digitais:

| Entrada | Descrição | Valor 0 | Valor 1 |
|---|---|---|---|
| M | Manutenção | Desativada | Ativada |
| T | Temperatura | Normal | Alta |
| P | Porta | Fechada | Aberta |

A partir dessas entradas, são determinadas duas saídas:

| Saída | Descrição |
|---|---|
| R | Acionamento da refrigeração |
| A | Acionamento do alarme |

## 🔢 Expressões booleanas

O funcionamento do circuito é baseado nas seguintes expressões:

- **Refrigeração:** `R = T · M̅`
- **Alarme:** `A = T · P`

A refrigeração é acionada quando a temperatura está alta e a manutenção está desativada. Já o alarme é acionado quando a temperatura está alta e a porta permanece aberta.

## 🖥️ Recursos do simulador

- Controles interativos para as três entradas digitais.
- Indicadores visuais para as saídas de refrigeração e alarme.
- Representação gráfica do circuito lógico.
- Tabela-verdade com as oito combinações possíveis.
- Destaque automático da combinação selecionada.
- Botões para testar situações específicas.
- Explicação dinâmica do comportamento do sistema.

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Tailwind CSS
- Lucide Icons

## ▶️ Como utilizar

1. Acesse o simulador pelo navegador.
2. Altere os controles de manutenção, temperatura e porta.
3. Observe as mudanças nas saídas do sistema.
4. Consulte o circuito lógico e a tabela-verdade para acompanhar os resultados.
5. Utilize os botões de situações predefinidas para facilitar os testes.

## 🧪 Validação do projeto

A montagem do circuito lógico e os testes práticos das combinações de entrada foram realizados no **Logisim**.

Este simulador web foi desenvolvido como recurso complementar para facilitar a visualização e a compreensão do funcionamento do sistema.

## 📚 Finalidade acadêmica

Projeto desenvolvido para fins educacionais, envolvendo conceitos de portas lógicas, álgebra booleana, tabela-verdade e sistemas digitais aplicados à automação de equipamentos de refrigeração.

---

**Disciplina:** Eletrônica Digital e Analógica  
**Projeto:** Sistema Inteligente de Monitoramento e Controle de Temperatura
**Discente:** Wesley Freitas

