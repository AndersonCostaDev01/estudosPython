# Pagina de estudos do UV

## o que e o UV 
> o uv e uma ferramenta para gerenciar pacotes e ambientes virtuais do Python, ele vem para subistituir o pip e o venv ao mesmo tempo sendo bem mais rapido e performatico 

## como usar o UV 
> para usar o UV primeiro e nessesario ter ele em sua maquina, a forma  mais facil de ter ele na maquina e usando o: 
```bash
pip install uv 
```
apos instalar ele em sua maquina para comecarmos a usar podemos criar uma pasta normal e iniciar ele 
```bash
uv init 
```
isso roda o uv na pasta criando a estrutura base do projeto

para adicionar alguma biblioteca podemos usar o ```uv add <biblioteca>``` e com isso iremos adicionar e ja cria de forma automatica o **venv** sem a nessesidade de rodar mais nada 

Agora para rodar o projeto podemos executar ```uv run <nome do arquivo>``` isso executa o arquivo ja dentro da venv sem mais dificuldades 

### Principais comando do UV 
```bash
# iniciar o UV 
uv init 
# se estiver querendo criar a pasta jundo do prjeto basta rodar o comando junto ao nome da pasta 
uv init <pasta>

# Adicionar biblioteca 
uv add <biblioteca>

# rodar arquivo
uv run <arquivo.py>

# Para remover bibliotecas e dependencias 
uv remover <biblioteca> 

# Sincroniza as dependencias do arquivo pyproject.toml e instala o que tiver faltando e desistala o que estiver sobrando 
uv sync
```