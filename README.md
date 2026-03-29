# 💱 Global Exchange - ConversorExpert

Este projeto representa a aplicação prática de conceitos de **IHC (Interação Humano-Computador)** e **UX (Experiência do Usuário)** em um sistema de console desenvolvido em C#.

---

## 🎯 Objetivo

Criar um conversor de moedas (Real → Dólar) que não apenas funcione corretamente, mas também ofereça uma boa experiência ao usuário.

---

## 🧠 Heurísticas de Nielsen Aplicadas

### 1️⃣ Visibilidade do Status do Sistema

O sistema mantém o usuário informado sobre o que está acontecendo.

💡 Aplicações no projeto:

* Mensagem: `"Conectando ao Banco Central..."`
* Animação com pontos (`Calculando taxas...`)
* Uso de `Thread.Sleep` para simular processamento

➡️ Isso transmite sensação de funcionamento real e evita incerteza.

---

### 2️⃣ Prevenção de Erros

O sistema evita falhas críticas e trata entradas inválidas.

💡 Aplicações no projeto:

* Uso de `try-catch` para capturar erros
* Mensagem clara ao usuário em caso de falha:
  `"Entrada inválida! Use apenas números..."`

➡️ Evita que o programa quebre e orienta o usuário corretamente.

---

### 3️⃣ Estética e Design Minimalista

A interface é simples, clara e focada no essencial.

💡 Aplicações no projeto:

* Uso de cores para destacar informações importantes:

  * Amarelo: título
  * Verde: resultado
  * Vermelho: erro
* Layout organizado com separadores (`---`)
* Exibição direta do resultado final

➡️ Reduz poluição visual e melhora a leitura.

---

## ▶️ Como executar

```bash
dotnet run
```

---

## 📸 Evidência

O arquivo `evidencia-final.png` mostra o sistema em execução com:

* Simulação de carregamento
* Conversão realizada com sucesso

---

## 🛠️ Tecnologias utilizadas

* C#
* .NET Console
* Conceitos de UX e IHC
