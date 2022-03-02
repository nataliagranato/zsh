# zsh
Zsh é um shell projetado para uso interativo, embora também seja uma poderosa linguagem de script.

# "Oh My ZSH!"
Agora vamos utilizar o Oh my Zsh para gerenciar as configurações do Zsh, neste caso utilizaremos as seguintes:

o spaceship-prompt: Spaceship é um prompt Zsh minimalista, poderoso e extremamente personalizável.

zsh-autosuggestions: Ele sugere comandos conforme você digita com base no histórico e nas conclusões.

zsh-syntax-highlighting: Este pacote fornece realce de sintaxe para o shell zsh. Ele permite o destaque de comandos enquanto eles são digitados em um prompt zsh em um terminal interativo. Isso ajuda na revisão de comandos antes de executá-los, principalmente na captura de erros de sintaxe.


# Clone os repositórios:
Spaceship

```git clone https://github.com/spaceship-prompt/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt" --depth=1```

Movendo para o diretório de temas personalizados oh-my-zsh:

```ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"```

Zsh-autosuggestions

```git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions```

Zsh-sintax-highlighting

```git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting```
