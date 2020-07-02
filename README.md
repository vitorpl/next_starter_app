# Next React Starter Proj

# Iniciar projeto
```
npm init -y
```

# instalar dependências
```
npm install next react react-dom
```

# Editar o package.json para rodar o next
```
"scripts": {
    "dev": "next",
    "run": "next start",
    "build": "next build"
  },
```

# Criar o index.js

```
import React from 'react'

const Index = () => {
    return <h1>App Next!</h1>
}

export default Index
```

# executar projeto

```
npm run dev
```


```
git rm -r --cached .next
git commit -m 'Remove .next from git project'
git push origin master
```