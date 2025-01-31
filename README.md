# Passos para actualizar Node.js Usando NVM

O **NVM (Node Version Manager)** permite instalar e gerenciar várias versões do **Node.js** no Ubuntu.

## **1. Instalar o NVM (se ainda não estiver instalado)**
```bash
curl -fsSL https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.4/install.sh | bash
source ~/.bashrc  # ou source ~/.profile
```

## **2. Listar Todas as Versões Disponíveis do Node.js**
Para ver a lista completa de versões do Node.js disponíveis para instalação:
```bash
nvm list-remote
```

## **3. Instalar uma Versão Específica do Node.js**
Substitua `<versão>` pela versão desejada. Exemplo, para instalar o Node.js **18.17.0**:
```bash
nvm install 18.17.0
```

## **4. Usar uma Versão Específica do Node.js**
Para alternar para uma versão específica do Node.js já instalada:
```bash
nvm use 18.17.0
```

## **5. Definir uma Versão Padrão do Node.js**
Se quiser que uma versão específica seja usada automaticamente em novas sessões do terminal:
```bash
nvm alias default 18.17.0
```

## **6. Verificar as Versões Instaladas**
Para listar todas as versões do Node.js instaladas no sistema:
```bash
nvm list
```

## **7. Confirmar a Versão do Node.js Ativa**
Para verificar qual versão do Node.js está atualmente em uso:
```bash
node -v
```

