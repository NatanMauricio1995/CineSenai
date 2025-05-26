# 🎬 CineSenai

> **Conectando mundos, transformando emoções**

Sistema de gerenciamento de cinema desenvolvido em Portugol, permitindo vendas de ingressos, produtos da bomboniere e relatórios de vendas.

## 📋 Funcionalidades

### 🎫 Sistema de Ingressos
- **Validação automática de preços**: O sistema calcula automaticamente se o cliente tem direito à meia-entrada baseado em:
  - Idade (menores de 18 anos ou idosos acima de 60 anos)
  - Situação escolar (estudantes matriculados)
  - Portadores de deficiência
- **Seleção de filmes**: 5 filmes disponíveis com diferentes horários
- **Mapa de poltronas**: Sistema visual de seleção de assentos (5x5)
- **Controle de disponibilidade**: Verificação automática de poltronas ocupadas

### 🍿 Bomboniere
- **10 produtos disponíveis**:
  - Combo (balde de pipoca + refrigerante grande)
  - Pipoca (pequena, média, grande)
  - Refrigerante (pequeno, médio, grande)
  - Nachos com queijo
  - Cachorro quente
  - Chocolate
- **Carrinho de compras**: Adicione múltiplos produtos e quantidades
- **Cálculo automático**: Total por item e valor final da compra

### 📊 Relatórios Gerenciais
- **Relatório de Ingressos**:
  - Vendas por filme
  - Quantidade de meias/inteiras vendidas
  - Faturamento detalhado por filme
  - Totais consolidados
- **Relatório da Bomboniere**:
  - Quantidade vendida por produto
  - Faturamento por item
  - Totais consolidados

## 🎯 Filmes em Cartaz

| Filme | Horário |
|-------|---------|
| Superman: O Legado | 14:00 |
| Capitão América: Admirável Mundo Novo | 16:00 |
| Lilo & Stitch | 18:00 |
| Lobisomem | 20:00 |
| O Agente Secreto | 22:00 |

## 💰 Tabela de Preços

### Ingressos
- **Inteira**: R$ 30,00
- **Meia**: R$ 12,50

### Bomboniere
| Produto | Preço |
|---------|-------|
| Combo | R$ 50,00 |
| Pipoca pequena | R$ 15,00 |
| Pipoca média | R$ 25,00 |
| Pipoca grande | R$ 35,00 |
| Refrigerante pequeno | R$ 10,00 |
| Refrigerante médio | R$ 15,00 |
| Refrigerante grande | R$ 20,00 |
| Nachos com queijo | R$ 30,00 |
| Cachorro quente | R$ 18,00 |
| Chocolate | R$ 12,00 |

## 🚀 Como Executar

### Pré-requisitos
- Ambiente de desenvolvimento Portugol (como o Portugol Studio)
- Compilador compatível com a sintaxe Portugol

### Instalação
1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/cine-senai.git
```

2. Abra o arquivo `CineSenai.por` no Portugol Studio

3. Execute o programa

## 🎮 Como Usar

### Menu Principal
1. **Venda de Ingressos**: Acesse o sistema de vendas de ingressos
2. **Bomboniere**: Acesse a loja de produtos alimentícios
3. **Saldo**: Visualize relatórios de vendas
4. **Sair**: Encerra o programa

### Fluxo de Venda de Ingressos
1. **Validação de idade**: Digite sua data de nascimento
2. **Informações complementares**: Responda sobre escolaridade e deficiência
3. **Seleção do filme**: Escolha entre os 5 filmes disponíveis
4. **Escolha da poltrona**: Selecione fileira (A-E) e coluna (1-5)
5. **Confirmação**: Sistema confirma a reserva

### Fluxo da Bomboniere
1. **Seleção de produtos**: Escolha produtos do menu
2. **Quantidade**: Defina a quantidade desejada
3. **Continuar comprando**: Adicione mais produtos se desejar
4. **Finalização**: Visualize o resumo da compra e total

## 🔧 Estrutura do Código

### Principais Componentes
- **Matrizes de Filmes**: Controle individual de poltronas para cada filme
- **Sistema de Validação**: Funções para determinar tipo de ingresso
- **Interface Visual**: Mapa de poltronas e menus formatados
- **Relatórios**: Consolidação de dados de vendas

### Constantes Configuráveis
```portugol
const inteiro IDADE_MENOR = 18
const inteiro IDADE_IDOSO = 60
const real PRECO_INTEIRA = 30.0
const real PRECO_MEIA = 12.5
```

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: Portugol
- **Bibliotecas**:
  - `Calendario`: Para validação de datas
  - `Texto`: Para manipulação de strings
  - `Matematica`: Para cálculos e arredondamentos

## 📈 Funcionalidades Técnicas

- **Validação de dados**: Entrada de dados com verificação
- **Persistência em memória**: Dados mantidos durante a execução
- **Interface amigável**: Menus intuitivos e feedback visual
- **Cálculos automáticos**: Preços e totais calculados automaticamente

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👥 Autores

- **Equipe SENAI** - Desenvolvimento inicial

## 🎯 Próximas Funcionalidades

- [ ] Sistema de desconto para estudantes
- [ ] Integração com sistema de pagamento
- [ ] Relatórios em formato de arquivo
- [ ] Sistema de reserva online
- [ ] Controle de estoque da bomboniere

---

**CineSenai** - Transformando a experiência cinematográfica através da tecnologia! 🎬✨
