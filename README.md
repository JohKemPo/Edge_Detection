<div align="center">
  <h1>Detecção de Bordas: Um Estudo Comparativo de Métodos de Interpolação</h1>
</div>
<p align = "justify"> &emsp; Este projeto consiste em um estudo comparativo de diversos métodos de detecção de bordas, com foco na aplicação de diferentes técnicas de interpolação. Os métodos investigados incluem Subsampling, Bicubic, Sharpened, Lanczos, Box, Generalized, Content-Adaptive e Perceptual (ours). O objetivo é analisar e comparar a eficácia de cada método na detecção precisa de bordas em imagens.</p>


<!-- APENDICE -->

<!-- <h2 id="apendice">Apêndice </h2> -->

<h3 id="env">Criação  de Ambiente Virtual em Python e instalação das dependências</h3>

**`Crie somente um ambiente virtual, após isso instale as dependências descritas na fase de instalação de dependências.`**

<h3 id="miniconda">(Opçãp 1) Criação - miniconda:</h3>

1. Baixar o instalador miniconda:
```
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```
2. Executando o instalador:
```
bash Miniconda3-latest-Linux-x86_64.sh
```
3. Iniciar coda:
```
conda init
```
4. Listar env existentes:
```
conda env list
```
5. Criar env com pytoh3.10:
```
conda create -n <name env> python=3.10
```
6. Ativar env:
```
conda activate <name env>
```

7. Deletar .sh
```
rm Miniconda3-latest-Linux-x86_64.sh
```

<br>
<h3 id="venv">(Opçãp 2) Criação - venv:</h3>

Para criar um ambiente virtual em Python, você pode usar a biblioteca padrão chamada `venv`. Siga as etapas abaixo para criar e ativar um ambiente virtual usando o `venv`:

1. Verifique se o Python 3 está instalado:
Abra o terminal e execute o seguinte comando:
```
python3 --version
```
2. Se o Python 3 já estiver instalado, você verá a versão instalada. Caso contrário, siga para o próximo passo.

3. Instale o Python 3:

No terminal, execute os comandos apropriados de acordo com a distribuição Linux que você está usando.

```
sudo apt install python3
```

4. Instale o pip:

```
sudo apt install python3-pip
```

5. Instale o pacote venv:
O pacote venv permite criar ambientes virtuais isolados. No terminal, execute o seguinte comando:

```
sudo apt install python3-venv
```

6. Para criação do ambiente virtual:
Navegue até o diretório onde deseja criar o ambiente virtual.

7. Digite o seguinte comando para criar um novo ambiente virtual:

```
python3 -m venv nome_do_ambiente
```

*Substitua "nome_do_ambiente" pelo nome que você deseja dar ao seu ambiente virtual.*

8. Para ativar o ambiente virtual, execute o comando apropriado de acordo com o seu sistema operacional:

```
source nome_do_ambiente/bin/activate
```

9. Agora, o ambiente virtual está ativado. Você pode instalar pacotes e executar seus projetos dentro dele sem afetar o ambiente global do Python.

Quando você terminar de trabalhar com o ambiente virtual, pode desativá-lo usando o comando:

```
deactivate
```

### **Extra**

Configurar para conda sempre inciarlizar em uma determinada env:

```
conda env list
export CONDA_DEFAULT_ENV="/caminho/para/env"
```

### **Instalação das dependências**

1. Instalação das dependências do projeto no **ambiente virtual**:

```
# instalar bibliotecas especificadas em um único arquivo
pip install -r requirements.txt

# instalar bibliotecas especificadas em multiplos arquivos
pip install -r requirements_1.txt -r requirements_2.txt
```

<h3 id="links">Links importantes:</h3>

- 

<br>
<h1 id="Equipe">Equipe</h1><br>

<div align="center">

|     Desenvolvedor              |           GitHub             |       LinkedIn     |
|--------------------------------|------------------------------|--------------------|
|👤 João Vitor Moraes            |<https://github.com/JohKemPo>   |<https://www.linkedin.com/in/joao-vitor-de-moraes/>|
</div>
