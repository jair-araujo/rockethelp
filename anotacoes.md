# React Native

## Estrutura básica de componentes

- Todo componente é uma função e tem um nome.
- Os componentes devem começar com letra maiúscula e o nome do arquivo também.
- Todo componente tem que retornar alguma coisas.
- Para ser utilizada em algum outro lugar deve ser exportado a função.
- Outra regra importante para se respeitar, componentes não devem retornar mais do que dois elementos. Logo os dados devem ser encapsolados dentro de um unico elemento, como no código abaixo a `<View>` envolvendo o `<Text>`.

```js
import { View, Text } from 'react-native';

export function SignIn() {
  return (
    <View>
      <Text>Olá, Jair!</Text>
    </View>
  );
}
```

## Tecnologias utilizadas e aprendizados

- React Native
- Native Base
- React Navigation
- Phosphor React Native (Biblioteca de icones)
- Expo
- Expo Bare Workflow
- React Native Firebase
- Fontes personalizadas (Validação do carregamento dessas fontes)
- Criação de componentes personalizados, passando parametros para eles.
- Filtros personalizados
