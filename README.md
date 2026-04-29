# 🦉 DevLingo - Gamified Learning Platform
**Desenvolvido por Ana Karoline Ribeiro**

![DevLingo Preview](./prints-projeto/gif/giphy-devLingo.gif)

O **DevLingo** é uma plataforma de ensino gamificada de alta fidelidade, inspirada no Duolingo, criada para transformar o aprendizado de tecnologia em uma experiência imersiva e interativa. Este projeto demonstra a aplicação de padrões avançados de desenvolvimento Frontend e integração robusta com serviços de Backend-as-a-Service.

---

## 🚀 Tecnologias Utilizadas

- **React 19 + TypeScript**: Desenvolvimento de interface com tipagem estrita para máxima segurança.
- **TanStack Router**: Gerenciamento de rotas moderno e totalmente type-safe.
- **Supabase**: Autenticação de usuários e Banco de Dados Relacional (PostgreSQL).
- **Tailwind CSS**: Estilização responsiva e focada em performance (Pixel Perfect).
- **Lucide React**: Biblioteca de ícones consistente e elegante.
- **Zod**: Validação de esquemas e dados de entrada.

---

## ✨ Funcionalidades em Destaque

- **🎯 Gamificação Completa**: Sistema de XP (Experiência), Níveis e Vidas (Hearts) para incentivar o engajamento e retenção.
- **⚡ Sincronização em Tempo Real**: Atualização instantânea do progresso do usuário no Header via WebSockets (**Supabase Realtime**).
- **🛤️ Trilha de Aprendizado**: Sistema de lições progressivas onde novas etapas são desbloqueadas conforme o desempenho do aluno.
- **📊 Feedback Inteligente**: 
  - **Sucesso**: Tela detalhada para desempenhos altos (>50% de precisão) com cards de XP.
  - **Recuperação**: Interface personalizada para incentivar a prática em caso de baixa performance.
- **🔐 Autenticação Segura**: Fluxo completo de Sign-in e Sign-up integrado com Supabase Auth.

---

## 🛠️ Arquitetura e Engenharia

- **Backend-as-a-Service (BaaS)**: Uso estratégico do Supabase para gerenciar a complexidade de servidor, mantendo a robustez de um banco PostgreSQL.
- **RPC (Remote Procedure Calls)**: Funções **PL/pgSQL** executadas diretamente no banco de dados para garantir integridade atômica na atualização de XP.
- **Roteamento Type-Safe**: Eliminação total de erros de navegação em tempo de compilação utilizando as definições do TanStack Router.
- **Gerenciamento de Estado**: Uso de Context API e Hooks customizados para um fluxo de dados limpo e escalável.

---

> ## 📄 Licença e Uso
> Este projeto foi desenvolvido por **Ana Karoline Ribeiro* para fins de portfólio profissional.
> **Todos os direitos reservados.**


---
