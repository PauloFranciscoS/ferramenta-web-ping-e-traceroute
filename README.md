# 🌐 Ferramenta Web de Ping e Traceroute

Uma ferramenta simples e intuitiva para realizar **ping** e **traceroute** a partir de múltiplas localizações ao redor do mundo.  
Permite diagnosticar a conectividade de rede e latência entre diferentes regiões e um domínio/IP alvo.

## 🚀 Funcionalidades

- Teste de **Ping** em múltiplas localizações.
- Execução de **Traceroute** para identificar o caminho até o destino.
- Interface limpa e moderna.
- Suporte a múltiplos servidores de origem:
  - 🇺🇸 **US East (Virginia)**
  - 🇺🇸 **US West (California)**
  - 🇩🇪 **Europe (Germany)**
  - 🇸🇬 **Asia (Singapore)**

## 📸 Captura de Tela

<img width="1082" height="667" alt="image" src="https://github.com/user-attachments/assets/d188c787-4afa-492f-b577-7dbe638710ff" />

## 🛠️ Tecnologias Utilizadas

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js (com bibliotecas para ping e traceroute)
- **Infraestrutura:** Pode ser hospedado em servidores locais ou na nuvem

## 📦 Instalação

Clone o repositório:

```bash
git clone https://github.com/PauloFranciscoS/ferramenta-web-ping-e-traceroute.git
cd ferramenta-web-ping-e-traceroute
```

## Instale as dependências:

```bash
npm install
```

Inicie o servidor:
```bash
npm start
```

## Acesse no navegador:

http://localhost:3000

## ⚙️ Como Usar

Digite um domínio ou IP no campo de entrada (ex: google.com ou 8.8.8.8).

Selecione as regiões de onde deseja rodar os testes.

Clique em Run.

Veja os resultados de ping e traceroute diretamente na interface.

## 📌 Roadmap

 Adicionar mais localizações.

 Exportar resultados em CSV/JSON.

 Melhorar visualização de traceroute (gráficos interativos).

 Autenticação de usuários (uso avançado).

## 🤝 Contribuindo

Contribuições são bem-vindas!
Siga os passos:

Faça um fork do projeto.

Crie uma nova branch (git checkout -b minha-feature).

Commit suas alterações (git commit -m 'Adicionei nova feature').

Envie para a branch principal (git push origin minha-feature).

Abra um Pull Request.

