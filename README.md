# log-archive

Ferramenta simples de linha de comando para compactar diretórios em arquivos `.tar.gz` com timestamp no nome.

## Instalação

1. Dê permissão de execução ao script:

```bash
chmod +x log-archive
```

2. Crie o diretório de binários locais (caso não exista):

```bash
mkdir ~/.local/bin/
```

3. Copie o script para o diretório:

```bash
cp log-archive ~/.local/bin/
```

## Uso


```bash
log-archive [diretório]
```

### Exemplo


```bash
log-archive /var/log/
```


