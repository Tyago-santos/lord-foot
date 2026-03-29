# Lord Foot

Aplicação web de delivery de comida, inspirada em plataformas como iFood. Permite que os usuários naveguem pelo cardápio, façam pedidos e acompanhem o status em tempo real.

## Tecnologias

- **Next.js 16** - Framework React com SSR e App Router
- **React 19** - Biblioteca de construção de interfaces
- **TypeScript** - Tipagem estática
- **Tailwind CSS 4** - Estilização utility-first

## Rodar Localmente (Next.js)

```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev

# Acessar http://localhost:3000
```

## Rodar com Docker

```bash
# Build da imagem
docker build -t lord-foot .

# Executar container
docker run -p 3000:3000 lord-foot

# Acessar http://localhost:3000
```

## Scripts Disponíveis

| Script       | Descrição                        |
|--------------|----------------------------------|
| `npm run dev`   | Inicia servidor de desenvolvimento |
| `npm run build` | Gera build de produção           |
| `npm run start` | Inicia servidor de produção      |
| `npm run lint`  | Executa linter ESLint            |

## Funcionalidades

- [x] Navegação pelo cardápio
- [x] Adicionar itens ao carrinho
- [x] Fazer pedidos
- [ ] Acompanhar status do pedido
- [ ] Cadastro de usuários
- [ ] Área do restaurante
