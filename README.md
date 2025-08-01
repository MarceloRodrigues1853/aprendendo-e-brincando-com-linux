
Este repositório reúne algumas configurações e aprendizados que estou fazendo enquanto exploro o mundo Linux, com foco em:

- Personalização do terminal com oh-my-posh
- Configuração do idioma do sistema para pt-BR
- Utilização do Windows Terminal com WSL
- Fontes nerd (Nerd Fonts) para exibição correta dos ícones

## 🌈 Tema do terminal

O tema utilizado e testado com sucesso foi o:

https://ohmyposh.dev/themes/jandedobbeleer.omp.json


Adicionado ao final do arquivo `~/.bashrc` com:

```bash
eval "$(oh-my-posh init bash --config https://ohmyposh.dev/themes/jandedobbeleer.omp.json)"
```

## 🔡 Fonte recomendada

Utilizei a MesloLGL Nerd Font, instalada manualmente no Windows e aplicada no Windows Terminal nas configurações do perfil WSL.

## 🛠️ Como aplicar

Instale o oh-my-posh

1. Configure o bashrc com o comando acima

2. Use o Windows Terminal e defina a fonte "MesloLGL Nerd Font"

3. Reinicie o terminal

📸 Print

## 📦 Conteúdo do repositório

.bashrc_com_oh-my-posh: versão do bashrc já com oh-my-posh configurado

.bashrc_original: backup da versão anterior

Pasta .poshthemes: onde você pode salvar seus temas customizados

Em breve, mais configurações e experimentações com terminal, pacotes e customizações!
